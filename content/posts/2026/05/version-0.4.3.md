---
title: "Novel-It Version 0.4.3"
date: 2026-05-07
slug: "novel-it-0.4.3"
pinned: false
tags: ["patches"]
---

A bug fix for scene relocation.

Scenes can be moved between chapters by dragging and dropping them. The move itself worked correctly, but clicking a relocated scene's link afterwards produced a 404 error. The scene's link still pointed at the original chapter rather than the one it had been moved to. Version 0.4.3 corrects this — the link is updated in place as soon as the move completes.
