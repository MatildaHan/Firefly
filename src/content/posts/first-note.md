---
title: 当时只道是寻常
published: 2026-09-18
description: 记个人博客装修过程，顺便记录一下踩过的坑。
image: "./images/1.avif"
tags: ["随笔", "博客", "Markdown"]
category: 随笔
draft: false
pinned: false
comment: true
---

## 起因

一直想有个自己的地方，写点东西。市面上的博客平台不少，但总感觉少了点什么，于是决定自己搭一个。

这篇文章记录一下整个装修过程，也给后来的人留个参考。

## 环境准备

需要的东西不多：

- Node.js ≥ 22
- pnpm ≥ 11
- Git

装好之后，克隆仓库、安装依赖、启动开发服务器，三步走。

```bash
git clone https://github.com/MatildaHan/Firefly.git Firefly
cd Firefly
pnpm install
pnpm dev