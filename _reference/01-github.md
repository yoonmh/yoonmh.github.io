---
title: 'Git, GitHub'
excerpt: "GitHub Pages를 이용해서 개인 블로그를 만들기 위한 방법을 정리했습니다."
layout: single
author_profile: false
header:
  image: /assets/images/earth.jpg
  teaser: /assets/images/github-cover.jpg
  show_overlay_excerpt: false
---

> GitHub Pages를 이용해서 개인 블로그를 만들기 위한 방법을 정리했습니다.

## Git

Git은 컴퓨터 파일의 변경사항을 추적하고 여러 명의 사용자들 간에 해당 파일들의 작업을 조율허ㅏ기 위한 분산버전관리시스템(Version Control System) 입니다.
* [Git](http://git-scm.com/)
* [Sourcetree](https://www.sourcetreeapp.com/): Git GUI 툴

Git의 동작
1. pull (fetch+merge를 한번에 가능) 받아 소스 받기
2. 수정
3. commit하여 로컬에 저장(서버가 아닌 로컬 저장소에 저장됨)
4. push 하여 서버에 업로드 하기 

## GitHub
GitHub는 분산버전관리툴인 Git을 사용하는 프로젝트를 지원하는 웹호스팅 서비스 입니다.
* [GitHub](https://github.com/)
* [Github Desktop](https://desktop.github.com/): 

Git을 사용하려면 master가 아닌 branches를 사용하는편이 좋습니다.
로컬에서 Branches를 생성하여 활용하는 방법과 서버에서 Branches를 활용하는 법을 포스팅합니다.
로컬 Branches : 생성과 사용만으로 서버에 영향을 미치지 않고 로컬에만 관리된다.
서버 Branches : 서버에서 생성하여 모든 개발자들이 접근하여 개발 가능하다.


