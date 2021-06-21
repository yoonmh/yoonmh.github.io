---
title: "GitHub Pages"
# excerpt: "GitHub Pages를 이용해서 개인 블로그를 만들기 위한 방법을 정리했습니다."
layout: single
header:
  overlay_image: /assets/images/earth.jpg
  teaser: /assets/images/github.png
#  show_overlay_excerpt: false
---

> GitHub Pages를 이용해서 개인 블로그를 만들기 위한 방법을 정리했습니다.

* [GitHub Pages](https://pages.github.com/)
* [GitHub Docs](https://docs.github.com/en/pages/getting-started-with-github-pages)

## Jekyll
지킬은 Ruby 언어로 작성된 정적 사이트 생성기

루비 설치 -> 지킬 설치 -> 블로그 제작 -> 깃허브 연동 -> 블로그 제작

* [Jekyll](https://jekyllrb.com/)
* [Ruby](https://rubyinstaller.org/)

테마
* http://jekyllthemes.org/
* https://jekyllthemes.io/
* https://jamstackthemes.dev/ssg/jekyll/
* https://jamstackthemes.dev/ssg/jekyll/
* http://themes.jekyllrc.org/

## Hexo
* [Hexo](https://hexo.io/)
* [Node.js](https://nodejs.org/en/)
* https://louisbarranqueiro.github.io/hexo-theme-tranquilpeak/
* https://hexo.io/themes/
* https://ppoffice.github.io/hexo-theme-icarus/

Hexo는 Jekyll와 함께 대표적으로 정적 페이지를 쉽게 만들 수 있도록 도와주는 서비스이다. 두 서비스 역시 블로그 지향적인 서비스이며 Hexo의 경우에는 npm을 통해 쉽게 설치가 가능하고 한 줄의 Command Line을 통해 Github에 바로 배포 할 수 있으며, Jekyll과 마찬가지로 다양한 플러그인과 테마를 지원하고 있다.
지킬은 Ruby기반이며, 헥소는 Node.js기반의 도구이다

1. Repository를 새로 만든다.
2. Repository이름은 바꿔야 함으로 아무렇 게나 짖는다.
3. Setting에 들어가서 Repository name을 다음과 같이 변경한다. [github id].github.io
4. 이름을 변경하고 나면 Setting > GitHub Page 의 내용을 보면 “ Your site is published at https://developern1.github.io/ “ 처럼 설정된 도메인을 확인할 수 있다.
5. Setting > GitHub Page의 “Choose a theme”버튼을 클릭하고 들어가서 테마를 고르거나, 다음 사이트에서 마음에 드는 테마를 고른 후 클릭하고 “Homepage”버튼을 클릭하면 해당 GitHub repository로 이동한다.
6. 이동한 후 Fork하면 위에서 개설한 repository에 테마가 등록된다.
7. 이제 테마의 설정을 수정하고 사용하면 된다.
8. Posting은 markdown으로 작성하여 _post directory에 보관한다.
github.com도 등록이 되지만 현재 정책적으로 .com은 .io로 r
