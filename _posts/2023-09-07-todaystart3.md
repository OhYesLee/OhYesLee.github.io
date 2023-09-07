---
layout: single
title:  "9월 7일 하루를 시작하며_3"
categories: [blog, Today, Start]
tag: [blog, today, start]
author_profile: false
use_math: true
---

<script>
window.onload = function(){
    updateCheckboxStatus();

    var checkboxes = document.querySelectorAll('input[type="checkbox"]');
    checkboxes.forEach(function(checkbox) {
        checkbox.addEventListener('change', updateCheckboxStatus);
    });
}

function updateCheckboxStatus() {
    var totalBoxes = document.querySelectorAll('input[type="checkbox"]').length;
    var checkedBoxes = document.querySelectorAll('input[type="checkbox"]:checked').length;
    document.getElementById("checkbox-status").innerHTML = `Checked: ${checkedBoxes} / Total: ${totalBoxes}`;
}
</script>

{: .notice--info}
2023-09-07 하루 일과 정리

<!-- <div id="checkbox-status"></div> -->

## 1. ***10:30 ~ 12:30*** 

- Blog 세팅
- 일과 정리하기
- 책읽기 ->
- 체크리스트 폼 만들기

## 2. 포모도로 시간법 ***Routine 25분 집중/5분 휴식***

## 3. 체크리스트

<div id="checkbox-status"></div>

- 출근
<div class="checkbox-inline">
    <label><input type="checkbox" checked> 출근시간 : ( )</label>
    <label><input type="checkbox" checked> 1.ebook 50~100: (책이름2)</label>
</div>    

- 공부 준비_1
<div class="checkbox-inline">
    <label><input type="checkbox"> 약</label>
    <label><input type="checkbox"> 단백질</label>
    <label><input type="checkbox"> 일정 작성</label>
    <label><input type="checkbox"> Github Blog 작동</label>
</div>

- 공부 준비_2
<div class="checkbox-inline">
    <label><input type="checkbox"> Github Blog 정리</label>
    <label><input type="checkbox"> Github Blog 세팅</label>
    <label><input type="checkbox"> 오늘 뉴스 확인하기</label>
</div>

- Analyze my project
<div class="checkbox-inline">
    <label><input type="checkbox"> Analyze my project</label>
    <label><input type="checkbox"> Analyze my project</label>
    <label><input type="checkbox"> Organize my project blog</label>
</div>

- Analyze my project
<div class="checkbox-inline">
    <label><input type="checkbox"> Analyze my project</label>
    <label><input type="checkbox"> Analyze my project</label>
    <label><input type="checkbox"> Organize my project blog</label>
</div>

- Analyze my project
<div class="checkbox-inline">
    <label><input type="checkbox"> Analyze my project</label>
    <label><input type="checkbox"> Analyze my project</label>
    <label><input type="checkbox"> Organize my project blog</label>
</div>

- Understanding my project
<div class="checkbox-inline">
    <label><input type="checkbox"> Understanding my project</label>
    <label><input type="checkbox"> Understanding my project</label>
    <label><input type="checkbox"> Organize my project blog</label>
</div>

- Understanding my project
<div class="checkbox-inline">
    <label><input type="checkbox"> Understanding my project</label>
    <label><input type="checkbox"> Understanding my project</label>
    <label><input type="checkbox"> Organize my project blog</label>
</div>

- Understanding my project
<div class="checkbox-inline">
    <label><input type="checkbox"> Understanding my project</label>
    <label><input type="checkbox"> Understanding my project</label>
    <label><input type="checkbox"> Organize my project blog</label>
</div>

- 퇴근
<div class="checkbox-inline">
    <label><input type="checkbox" checked> 퇴근시간 : ( )</label>
    <label><input type="checkbox"> 1.ebook 50~100: (책이름)</label>
</div>    

- Infearn
<div class="checkbox-inline">
    <label><input type="checkbox"> 인프런 강의듣기</label>
    <label><input type="checkbox"> 인프런 강의듣기</label>
</div>

- 면접책
<div class="checkbox-inline">
    <label><input type="checkbox"> 면접책 50~100</label>
    <label><input type="checkbox"> 면접책 블로그 및 굿노트 정리</label>
</div>

- 오늘은 약을 먹지 않아서 평소보다 더 집중이 안되고 졸리다.
- 약은 어제 챙겼다고 생각했는데 챙기지 못했다...

<!-- <br> -->

## 4. ***10:55 ~ 12:30*** 소스분석

- 명상 후 다시 집중하기



***

    언제나 나를 믿고 차근차근 매일 공부하며
    앞으로 나아가겠습니다.

<br>

***Promise <br> 1. 지식을 즐긴다. <br>2. 다른 사람의 말을 끝까지 듣는다. <br>3. 논리적으로 얘기하고 토론한다.***

<br>

[맨 위로 이동하기](#){: .btn .btn--primary }{: .align-right}
