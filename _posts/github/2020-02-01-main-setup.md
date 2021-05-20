---
title: 'Main 상단바 설정하기'
author: Myung-Hyun Yoon
layout: single
permalink: /main-setup/
toc: true
header:
  overlay_image: /assets/images/space.jpg
categories:
  - GitHub
sidebar:
  nav: "posts"
---

> Main 화면의 살단바 설정

## 1. 메뉴바 설정

`_sass/minimal-mistakes/_masthead.scss` 파일에 메뉴바 설정에 관한 내용이 있다. 
메뉴의 텍스트 크기, 여백 등을 지정할 수 있다.
```
/*padding: 1em;*/
padding: 0.4em;
```

```
font-size: $type-size-4;
font-weight: bold;
```

## 2. 하이퍼링크 밑줄 없애기
`_sass/minimal-mistakes/_base.scss`

```
text-decoration: none;
```
