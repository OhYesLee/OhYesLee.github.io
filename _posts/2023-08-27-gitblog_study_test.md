---
layout: single
title:  "Jekyll: 가볍게 시작하는 정적 사이트 생성기"
categories: [blog, jekyll, coding, tutorial]
tag: [blog, jekyll, github, Jekyll, web, coding]
author_profile: false
---

**[공지사항]** [Jekyll에 대해 배우기 좋은 리소스와 함께하는 블로그 글입니다!]
{: .notice--success}

# Jekyll이란?

Jekyll은 간단한, 정적 사이트 생성기입니다. Markdown, Liquid, HTML & CSS를 사용하여 빠르고 안정적인 사이트를 만들 수 있습니다. GitHub Pages와의 통합으로 인해 인기를 얻었으며, 많은 개발자들에게 블로그나 프로젝트 페이지를 쉽게 호스팅할 수 있는 방법을 제공합니다.

## Jekyll의 주요 특징

1. **정적 사이트 생성기**: 서버 사이드 로직이나 데이터베이스 없이 HTML, CSS, JS 파일만으로 웹사이트를 만듭니다.
2. **마크다운 지원**: 복잡한 HTML이나 템플릿 없이 글을 쓸 수 있습니다.
3. **Liquid 템플릿 엔진**: 간단한 템플릿 언어를 사용하여 데이터를 렌더링합니다.
4. **커스터마이징**: 플러그인을 사용하거나 직접 만들어 기능을 확장할 수 있습니다.

# Jekyll 설치 및 시작하기

```bash
# Ruby를 설치합니다.
sudo apt-get install ruby-full

# Jekyll과 bundler gems를 설치합니다.
gem install jekyll bundler

# 새로운 Jekyll 사이트를 생성합니다.
jekyll new my-awesome-site

# 생성된 폴더로 이동 후, 사이트를 빌드하고 서버를 시작합니다.
cd my-awesome-site
bundle exec jekyll serve
```