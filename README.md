# EasyBangumi

[English](README.md) | [中文](README-zh.md)

<a name="english"></a>

## Overview

**EasyBangumi** is a simple anime tracking page developed with Vue, supporting anime information display and progress management, suitable for personal use to record and review watched anime series.

---

## Quick Start

### 1. Install Dependencies

This project uses [pnpm](https://pnpm.io/) for package management.

```bash
pnpm install
```

### 2. Development Server

```bash
pnpm dev
```

### 3. Production Build

```bash
pnpm build
```

---

## Data Format

Anime data is stored in `public/data/animeData.json` with the following format:

```json
[
  {
    "title": "Anime Title",
    "description": "Anime Description",
    "year": broadcast year,
    "total_episodes": total episodes,
    "progress_text": "Watch Progress",
    "cover": "Photo/xxx.jpg",
    "status": "Anime Status"
  }
  // ...more anime entries
]
```

---
If you have any questions, feel free to raise an `Issue` or submit a `PR`!
---