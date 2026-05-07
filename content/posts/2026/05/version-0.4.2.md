---
title: "Novel-It Version 0.4.2"
date: 2026-05-07
slug: "novel-it-0.4.2"
pinned: false
tags: ["patches"]
---

A few word count fixes in this release.

When a chapter was archived or deleted, the word counts for the parent part and novel were not updated to reflect the change. Separately, deleting a scene also failed to update the word count of its parent chapter, part, or novel. Archiving and restoring scenes were already working correctly.

These issues are now fixed.
