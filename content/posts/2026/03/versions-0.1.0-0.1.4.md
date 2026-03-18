---
title: "Novel-It Versions 0.1.0 to 0.1.4"
date: 2026-03-18
slug: "novel-it-0.1.4"
pinned: false
tags: ["patches"]
---

### Novel-It Early Updates

Novel-It was originally "released" to GitHub as v0.1.0 - a working application but not yet ready for a formal release. As with the way of things, as soon as I'd uploaded it, I started to find a few bugs and there have been a number of patch releases since then. This post summarises those patches. Going forwards there will be individual posts for each Novel-It update.
<!--more-->
#### v0.1.1

- Added the [Installation Guide v1](https://github.com/david-hollingworth/novel-it/blob/development/docs/novel-it-installation-guide.md)
- Added the [Feature Specification v2](https://github.com/david-hollingworth/novel-it/blob/development/docs/novel-it_feature_specification_v2.md) missed from the initial release.

#### v0.1.2

Replaced the EasyMDE editor with a bespoke mrkdown editor developed specifically for Novel-It, but based on `editor.js`.

#### v0.1.3

Fixed missing field labels on the registration form.

#### v0.1.4

Resolved two issues with the editor:

1. The 30 second auto-save wasn't working
2. You could navigate away from the editor with changes not saved. This esulted in work being lost.