---
title: "Novel-It Version 0.5.1"
date: 2026-06-15
slug: "novel-it-0.5.1"
pinned: false
summary: "This version patches fixes a bug in the preview rendering of scenes."
tags: ["patches"]
---

The scene editor supports basic formatting using Markdown syntax, and the editor provides a preview mode so the writer can review what the final document will look like.By default Markdown requires two blank lines between paragraphs, which is fine if you're starting a new paragraph, but in dialogue you want the next sentence to start on the following line. Like this:

"Hello," said John. "My name is John."

"Hello John." replied Jill. "Have you got a light?"

"Sorry, I don't smoke."

In the preview output this rendered as 

"Hello," said John. "My name is John." "Hello John." replied Jill. "Have you got a light?" "Sorry, I don't smoke."

Not ideal. In version  0.5.1 this is fixed so that dialogue is rendered on separate lines in the preview, with no blank lines in between.