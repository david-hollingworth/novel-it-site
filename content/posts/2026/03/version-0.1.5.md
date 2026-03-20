---
title: "Novel-It Version 0.1.5"
date: 2026-03-19
slug: "novel-it-0.1.5"
pinned: false
tags: ["patches", "installation guide"]
---

I've rolled two important fixes into this patch release:

### Bullets and Number Lists Not Displaying Correctly

If you created a bulleted (unordered) or numbered (ordered) list in the scene editor then the bullets or numbers did not display when you clicked the Preview button. You still got an indented list, but without the bullets or numbers. This is now resolved.

### Incorrect gunicorn Command in the Installation Guide

`gunicorn` is the command you run to start the application server. In the installation guide the command wad given as:

`gunicorn --bind 0.0.0.0 novelapp.wsgi`

This command works, but the application is unstable becuase it doesn't start enough gunicorn workers. To rectify this I have introduced a new configuration  file `gunicorn.conf.py`. This file manages the number of gunicorn workers created, as well as a number of other parameters, including the bind value.

As a result the command to start the server is now just:

`gunicorn novelapp.wsgi`

The installation guide has been updated to reflect this.