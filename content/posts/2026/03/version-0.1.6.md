---
title: "Novel-It Version 0.1.6"
date: 2026-03-20
slug: "novel-it-0.1.6"
pinned: false
tags: ["patches"]
---

Novel-It v0.1.6 fixes an issue that carries the obscure title "Vendor all external frontend dependencies". What on earth does that mean?

When an application, such as Novel-It, is developed it sometimes (often) relies on external code libraries that are pulled foim the Internet everytime the application is run. For example, Novel-It uses external libraries to provide the ability to drag and drop the chapter and scene cards and external libraries are used to provide the fonts used.
<!--more-->
So this is all very well, and is a standard software development practice. However, Novel-It needs to work offline. Just imagine you're on a flight, or in some distant café with no Internet, and you fancy doing some writing with your new installation of Novel-It. You'd be pretty miffed if the application didn't work at all because it had no access to its external dependencies.

The solution to this is to "vendor" the dependencies. Vendoring is the process of installing locally the external dependencies. Then the application will still work if there's no internet access. 