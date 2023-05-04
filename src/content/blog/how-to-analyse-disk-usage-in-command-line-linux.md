---
author: universeroc
pubDatetime: 2023-05-04T02:08:05.690Z
title: How To Analyse Disk Usage In Command Line Linux
postSlug: how-to-analyse-disk-usage-in-command-line-linux
featured: true
draft: false
tags:
  - linux
  - disk space
ogImage: ""
description: How To Analyse Disk Usage In Command Line Linux
---

```bash
du -h 2> /dev/null | sort -hr | head -n20
```

> [](https://superuser.com/questions/300606/how-to-analyse-disk-usage-in-command-line-linux)
