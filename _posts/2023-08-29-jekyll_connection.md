---
layout: single
title:  "Jekyll: 로컬로 연결해서 바로 확인하기"
categories: [blog, jekyll, Jekyll]
tag: [blog, jekyll, github, local, Jekyll]
author_profile: false
use_math: true
---

**[공지사항]** [지킬블로그: Installation ](https://mmistakes.github.io/minimal-mistakes/docs/installation/)
{: .notice--success}

{: .notice--info}
2023-08-29 지킬 블로그 연습

# 테디노트 GitHub 블로그 시즌1 - Ep03.
{% include video id="0TeHUqSAb6Q" provider="youtube" %}

## 터미널에서 서버 구동


```terminal
bundle exec jekyll serve
```

## 지속적으로 추가

<!-- {: .align-right} -->
- 미리 CSS형태로 스타일링이 들어가있고 간단한 기호로 마크다운으로 표시를 하는 것이다. 이런 원리를 이용해서 커스텀 CSS를 적용할 수 있다.
- _utilities.scss로 들어간다 ->
```terminal
.img-width-half{
  width: 50%;
}
```
작성한다.

<!-- {: .align-right} -->

<!-- {: .align-right} -->
- 우측정렬 방법 ->
```terminal
=>{: .align-right}
```
<!-- {: .align-right} -->

- test


<img width="712" alt="스크린샷 2023-08-29 오전 10 58 27" src="https://github.com/OhYesLee/OhYesLee.github.io/assets/103974953/f09587e0-3bdb-4e08-bf1e-ae5ded77146a">{: .img-width-half .align-center}

<img width="1293" alt="스크린샷 2023-08-29 오전 10 58 34" src="https://github.com/OhYesLee/OhYesLee.github.io/assets/103974953/7c765d7c-8da6-4870-83e7-ebb55fea9c42">{: .img-width-half .align-center}

<img width="638" alt="스크린샷 2023-08-29 오전 10 59 19" src="https://github.com/OhYesLee/OhYesLee.github.io/assets/103974953/4eea52d1-7ecf-45d4-80de-ec6d20f4b4ef">{: .img-width-half .align-center}




## head -> custom.html
**추가로 사용하고 싶은 자바스크립트 코드나 CSS를 적용할 수 있다.**

# LaTeX는
LaTeX는 과학자와 엔지니어를 위한 문서 준비 시스템 및 마크업 언어로서, 특히 수학 및 물리학에서 많이 사용됩니다. 이 포스트에서는 LaTeX를 사용하여 수식을 작성하는 방법에 대한 몇 가지 예를 제공하겠습니다.

## 기본 수식

수식을 입력할 때는 `$( ... \)$` 또는 `$[ ... \]$`, `$ ... \$`로 수식을 감싸줍니다.

예를 들어, 직선의 기울기를 나타내는 수식:

$ y = mx + c \$

$ (y = mx + c \)$

$ [y = mx + c \]$

## 제곱과 제곱근

$[ a^2 = b \]$
$[ \sqrt{a^2 + b^2} \]$

## 적분

$[ \int_a^b f(x) \, dx \]$

## 행렬

$[
\begin{matrix}
a & b \\
c & d \\
\end{matrix}
\]$

이렇게 LaTeX를 사용하면 복잡한 수학적 표현도 아름답게 표현할 수 있습니다. Jekyll에서는 MathJax 라이브러리를 사용하여 이러한 수식을 렌더링하므로 웹 브라우저에서도 깨끗하게 표시됩니다.

더 많은 수식 예제와 LaTeX의 다양한 기능을 알고 싶다면 [LaTeX 위키북](https://en.wikibooks.org/wiki/LaTeX)을 참조하십시오.


## 배포 브랜치 설정 & 배포 시점 확인 방법

GitHub에서 블로그 레포로 들어간다

Commit을 진행한 후 merge를 하면 Actions에서 보인다.

클릭해서 과정을 보면된다.
<img width="722" alt="스크린샷 2023-08-29 오후 12 18 22" src="https://github.com/OhYesLee/OhYesLee.github.io/assets/103974953/23914675-2ad8-4280-9c22-e5d03a65d43a">{: .img-width-half .align-center}
