---
bg: "tools.jpg"
layout: post
title:  "HTML (6) - Form Tag"
crawlertitle: Markdown sample
summary: Script for HTML page 6
date:   2024-04-28
categories: posts
tags: ['front-end']
author: JUDAMaB
bg: "sea_otter.jpg"
---

위 문서에서는 폼 태그에 대해 공부한다.

## Form Tag

사용자가 입력한 입력 값을 서버로 보내기 위해 사용하는 태그

## 서버-클라이언트

클라이언트(사용자)가 요청을 하면 서버는 이에 응답한다. 사용 방식은 `<form>~</form>` 명령어를 이용한다. 이는 입력 요소들을 감싸며, 입력 값을 서버측으로 제출한다. 제출 시 `<input>` 태그의 submit 타입을 사용한다.

```html
<form>
	<input type="text" placeholder="아이디">
	<br>
	<input type="text" placeholder="비밀번호">
	<br>
	<input type="submit" value="로그인">
</form>
```

## Form 의 속성

- action: 입력값을 전송할 서버의 url
- method: 클라이언트가 입력한 데이터를 어떤 식으로 전송할 지(GET/POST)
 - GET: 서버에 요청을 보내어 응답을 받아냄 (서버의 정보를 가져옴)
 - POST: 서버에 요청을 보내어 작업을 수행함(서버의 정보를 조작함)

```html
<form action="exam.php" method="POST">
      <input type="text" placeholder="NAME" name="name">
      <br>
      <select name="pet">
          <option value="dog">강아지</option>
          <option value="dog">고양이</option>
          <option value="dog">기니피그</option>
      </select>
      <br>
      <input type="submit" value="전송">
</form>
```

실행화면 ->
[![Result]({{ site.images | relative_url }}/result.jpg)]({{ site.images | relative_url }}/result.jpg)

