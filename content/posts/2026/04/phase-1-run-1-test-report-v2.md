---
title: "Phase 1 Run 1 Test Report Version 2.0"
date: 2026-04-20
slug: "phase-1-run-1-test-report-v2"
pinned: false
tags: ["testing"]
---


After publishing the test report for phase 1, run 1 I realized I'd made a monumental cock-up (technical term) in the tests that were being flagged as untestable due to functionality that wasn't scehduled for phase 1.

In fact, all the requirements in [02-novel-management](https://david-hollingworth.github.io/novel-it-docs/requirements/02-novel-management/) and [03-writing-interface](https://david-hollingworth.github.io/novel-it-docs/requirements/03-writing-interface/) are phase 1 requirements. The fact that I had tests failing because functionality hadn't been implemented, these were *genuine failures* and not "untestable" tests. 

I have now corrected the [test report](https://david-hollingworth.github.io/novel-it-docs/test-results/phase-1/run-1/) to reflect the change in status of these test and to ensure they're all included in the run-2 test schedule.