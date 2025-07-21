# EasyBangumi

[English](README.md) | [中文](README-zh.md)

## 项目概述

**EasyBangumi** 是一个基于Vue开发的简单追番记录页面，支持番剧信息的展示与进度管理，适合个人用于记录和回顾已追番剧。

---

## 快速开始

### 1. 安装依赖

本项目使用 [pnpm](https://pnpm.io/) 进行包管理

```bash
pnpm install
```

### 2. 本地开发启动

```bash
pnpm dev
```

### 3. 构建生产环境

```bash
pnpm build
```

---

## data 数据格式说明

番剧数据存放于 `public/data/animeData.json`，其格式如下：

```json
[
  {
    "title": "番剧标题",
    "description": "番剧简介",
    "year": 播出年份,
    "total_episodes": 总集数,
    "progress_text": "观看进度",
    "cover": "Photo/xxx.jpg",
    "status": "番剧状态"
  }
  // ...更多番剧
]
```

--- 
如有问题欢迎提 `Issue` 或 `PR`！
---