---
layout: post
title: 'Post: Future Date'
date: 9999-12-31
categories:
- Post
last_modified_at: 2017-03-09T17:45:25.000+00:00

---
This post lives in the future and is dated {{ page.date | date: "%c" }}. It should only appear when Jekyll builds your project with the `--future` flag.

```bash
jekyll build --future
```