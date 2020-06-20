# Spring_Project_Test
# 마크다운(Markdown) 문서
확장자 .md로 된 파일들 
HTML (markup language) 대체 기능

1. 장점
    - 간편하고 쉽다
    - 다양한 플랫폼에서 지원
2. 단점
    - 표준이 없다. (표현 매체마다 다르게 보임)
    - 모든 HTML 태그를 대체하진 못한다
---
# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6
# 수평선(Horizontal Line)
각 기호를 3개 이상 입력

---

***
___

# 줄바꿈 (LineBreak)
'두번 띄어스기' 나 `<br>`로 사용하면 된다

동해물과 백두산이
마르고 닳도록
하느님이 보우하사
우리나라 만세


동해물과 백두산이
마르고 닳도록 <br>
하느님이 보우하사
우리나라 만세

# 이탤릭, 굵기
이탤릭은 *별표사용* `*별표사용*` 혹은 _언더바_ `_언더바_`

**이탤릭 굵게** `**이탤릭 굵게**` <br>

~~취소선~~ `~~취소선~~`

<u>밑줄</u> 은 `<u></u>`

# 목록

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
   - 순서가 필요하지 않은 목록
     - 순서가 필요하지 않은 목록
   - 순서가 필요하지 않은 목록

# 링크
[GOOGLE](https://www.google.com)

[GitHub](https://github.com)

# 이미지
![대체 텍스트 : trulli](https://www.w3schools.com/html/pic_trulli.jpg)

[![대체 텍스트 : trulli](https://www.w3schools.com/html/pic_trulli.jpg)](https://www.naver.com)

# 코드 강조
### 인라인 코드 강조
`background` 혹은 `background-image` 속성으로 배경이미지 삽입

### 블럭 코드 강조
` 를 3번 이상 입력하고 코드 종류도 적습니다.

```html
<a href="https://www.naver.com" target="_blank">네이버</a>
```

```java
System.out.println("");
public static void myFunction(String str){
    System.out.println(str);
}
```

```css
.list > ul {
    position: absolute;
    top : 40px;
}
```

# 표 (Table)
`<table>` 로 변환
|aa|bb|
|--|--|
|1|2|
|3|4|

### 열병합

|col1|col2|col3|col4|
|--|--|--|--|
|No span| Span  fffffffff ||

<br>

|값|의미|기본값|
|---|:----:|:---:|
|static| 배치 불가 | 12341234|
| abc | asdf| 123|
| ffffffff| asdfasdfasdf| 1|

# 인용문

> 남의 말이나 글에서 직접 따온 문장
>> 중첩 인용문
>>> 중중첩 인용
>>> test1
>>> test2
