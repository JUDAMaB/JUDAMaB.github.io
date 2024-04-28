---
bg: "bird.jpg"
layout: post
title:  "HTML (7) - Meta Tag"
crawlertitle: "About ES6"
summary: "Script for HTML page 7"
date:   2024-04-29 20:09:47 +0700
categories: posts
tags: ['front-end']
author: JUDAMaB
---

## Meta Tag

메타 태그는 html 문서에 대한 메타 데이터를 정의한다.
제공하는 메타 데디어 유형과 속성은 다음과 같다:

- charset: 문자 세트
- http-equiv: 콘텐츠 속성 정보에 대한 http 헤더
- name: 문서 정보
- content: 메타 데이터 내용

#### Charset

문자 인코딩에 대한 정보를 기입하는 속성이다. 

```html
<meta charset="utf-8">
```

#### http-equiv

콘텐츠 속성의 정보/값에 대한 HTTP 헤더를 제공한다.

#### name/content

- name: 문서의 다양한 정보를 제공할 수 있는 메타 데이터의 이름
- content: 메타 데이터의 구체적인 내용을 기입하는 속성
- name 속성을 이름으로, content 속성을 값으로 하여 문서 정보를 이름+값 쌍의 형태로 제공할 때 사용할 수 있다.

```html
<head>
    <meta charset="utf-8">
    <title>메타 태그</title>
</head>
<body>
    <h1>메타 태그 사용하기</h1>
    <meta http-equiv="x-ua-compatible" content="IE=edge">
    <meta name="author" content="Oong">
    <meta name="keywords" content="Creative, Brave, Busy">
    <meta name="description" content="How to Add Meta Tag">
</body>
```

## Viewport

현재 화면에 보여지고 있는 영역이다. 기기별 뷰포트가 다르다. 동일한 웹 페이지라도 기기에 따른 배율 조정이 발생해 화면의 크기가 다르게 보이는 현상이 나타날 수 있다.

```html
<head>
    <meta charset="utf-8">
    <meta name="viewport"
      content="width=device-width, initial-scale=1.0">
    <title>뷰포트 실습</title>
</head>
<body>
    <h1>메타 태그 사용하기</h1>
    <h1>메타 태그 사용하기</h1>
    <h1>메타 태그 사용하기</h1>
    <h1>메타 태그 사용하기</h1>
</body>
```
