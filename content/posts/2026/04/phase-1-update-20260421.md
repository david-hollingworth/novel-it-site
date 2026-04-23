---
title: "Phase 1 Update"
date: 2026-04-21
slug: "phase-1-progress-20260421"
pinned: false
tags: ["roadmap", "release"]
---

After the Phase 1, Run 1 testing there are quite a number of things that need fixing before we can move forward to a run-2 test phase. The work to do falls into these categories:

## Features

There are three phase-1 features that escaped implementation. These are:

- FEAT-0225 - Archive scene
- FEAT-0226 - Unarchive scene
- FEAT-0227 - Delete scene

These missing features were responsible for many of the test failures that required the archiving, restoration or deletion of a scene as part of the test protocol. As the functionality was missing the tests failed.

## Bugs

I'm not going to list all the bugs here, you can see them in the [issues list](https://github.com/david-hollingworth/novel-it/issues) on GitHub. However, they fall into three broad categories:

1. The word counts not adjusting correctly when chapters or parts are archived or deleted.
2. Fields detaled in the requirements were missing from the add or edit forms. 
3. Others

The "others" consist of a very small number of bugs, including a "page not found" error after moving a scene from one chapter to another.

## What's next

But before fixing the bugs and adding the missing features I'm going to work on an enhancement to the design and layout of the "cards" that are used to provide navigation to all the novel and planning elements. I've noticed some differences in the display and features of the cards in different parts of the application and these are essential for a consistent look and feel across the parts of the application so I want to get these all looking and working the same before moving forwards.