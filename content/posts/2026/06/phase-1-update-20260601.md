---
title: "Phase 1 Update"
date: 2026-06-01
slug: "phase-1-progress-20260601"
pinned: false
tags: ["release", "patches"]
---

Here we are, first day of June 2026, so I thought it was high time I provided an update on the state of Phase 1. I admit, May was fairly quiet, but this was mainly due to the SSD in my development system failing. Fortunately I had an alternative available, but the work to set this up and recover the development and test environments rather interrupted the workflow.

Having said that, I did get some patches committed in May. This is a brief summary of each:

### Version v0.4.4

Added many missing form fields and corrected the labels on others to align the forms with the requirements

### Version v0.4.5

Incorporated into v0.4.6

### Version v0.4.6

Navigating away from a scene with unsaved changes triggers a warning. Some of those notifications where handled by the application, but some were being captured by the browser. This patch ensures all these warnings are handled within the application.

The requirements state that only PNG and JPG/JPEG images could be uploaded to the planning entities (characters, locations etc) but this filter hadn't been implemented meaning you could attach all sorts of nonsense as the entity avatar.

### Version v0.4.7

This patch resolves an issue related to editing relationships where the forward relationship description was overwritten by the reverse relationship description.