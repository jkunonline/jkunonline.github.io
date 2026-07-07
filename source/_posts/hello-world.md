---
title: 维护日志模板
date: 2026-07-07 12:00:00
tags:
  - 维护日志
  - Hexo
categories:
  - 日常维护
cover: /img/poke-log-cover.svg
description: 用于确认 Hexo 站点、AnZhiYu 主题和 GitHub Pages 发布流程的维护日志模板。
---

这是一篇用于确认站点样式和发布流程的维护日志模板。以后可以把每次巡检、部署、故障排查都按类似结构记录下来。

## 背景

- 站点：`jkunonline.github.io`
- 类型：Hexo + GitHub Actions
- 目标：记录日常维护日志和技术日志

## 操作记录

```sh
npm run build
git add .
git commit -m "update log"
git push
```

## 结果

GitHub Actions 构建成功后，网站会自动更新。后续可以把这篇文章改成自己的真实维护记录。
