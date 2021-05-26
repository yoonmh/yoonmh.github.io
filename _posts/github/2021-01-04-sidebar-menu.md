---
title: 'Sidebar 메뉴 설정'
layout: single
sidebar_main: true
author_profile: true
header:
  overlay_image: /assets/images/earth.jpg
  show_overlay_excerpt: false
categories:
  - Github Pages
---

> Sidebar 메뉴 설정

## 1. '/_data/navigation.yml'

```
# sidebar categories
posts:
  - title: CATEGORIES
    children:
      - title: "Quick-Start Guide"
        url: /docs/quick-start-guide/
      - title: "Structure"
        url: /docs/structure/
      - title: "Installation"
        url: /docs/installation/
      - title: "Upgrading"
        url: /docs/upgrading/
```

## 2. 

```
---
sidebar:
  nav: "posts"
---
```
