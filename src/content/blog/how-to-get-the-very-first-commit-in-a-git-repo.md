---
author: universeroc
pubDatetime: 2023-04-27T07:14:21.783Z
title: How to get the very first commit in a Git Repo
postSlug: how-to-get-the-very-first-commit-in-a-git-repo
featured: true
draft: false
tags:
  - git
  - log
  - commit
ogImage: ""
description: How to get the very first commit in a Git Repo
---

```bash
git log --reverse
```

You can not use `--reverse` and `-1` at the same time!

The first commit of `git commit --reverse` is which you want.
