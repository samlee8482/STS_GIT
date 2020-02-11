# 마크다운(Markdown) 문서

확장자 .md 로 된 파일들
HTML (markup language)대체 기능

1. 장점
   - 간편하고 쉽다
   - 다양한 플랫폼에서 지원
2. 단점 
   - 표준이 없다. (표현매체마다 다르게 보임)
   - 모든 HTML 를 대체하진 못한다.

---

# 제목1
## 제목2
### 제목3
#### 제목4
##### 제목5
###### 제목6


# 수평선 (Horizontal line)
각 기호를 3개 이상 입력

---

***

___

# 줄바꿈 (Line break)
'두번 띄어쓰기' 나 `<br>` 로 사용하면 된다

동해물과 백두산이
마르고 닳도록
하느님이 보우하사
우리나라 만세

동해물과 백두산이
마르고 닳도록<br>
하느님이 보우하사
우리나라 만세

# 이탤릭, 굵게

이탤릭은 *별표* 사용 혹은 _언더바_ 사용
**이탤릭 굵게** <br>
~~취소선~~ <br>
<u>밑줄</u> 은 `<u></u>` 사용

# 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
   - 순서가 필요하지 않은 목록
   - 순서가 필요하지 않은 목록
   - 순서가 필요하지 않은 목록
     - 순서가 필요하지 않은 목록
     - 순서가 필요하지 않은 목록 
2. 순서가 필요한 목록
3. 순서가 필요한 목록
4. 순서가 필요한 목록
5. 순서가 필요한 목록

# 링크
[GOOGLE](https://google.com)

[GitHub](https://github.com)

# 이미지
![대체텍스트](https://www.w3schools.com/html/pic_trulli.jpg)

[![대체텍스트](https://www.w3schools.com/html/pic_trulli.jpg)](https://www.naver.com)

# 코드강조
### 인라인 코드 강조
`background` 혹은 `background-image` 속성으로 배경이미지 삽입

### 블럭코드강조
` 를 3번 이상 입력하고 코드 종류도 적습니다.

```html
<a href="https://www.naver.com" target="_blank">네이버</a>
```

```css
.list > li {
    position : absolute;
    top : 40px;
}
```

```java
public static void myFunction(int n, String str){
    System.out.println("Hello World");
}
```

# 표 (테이블)
`<table>` 로 변환

|aa|bb|
|--|--|
|1|2|
|3|4|

### 열병합
|Col1|Col2|Col3|Col4|
|----|----|----|----|
|No span| Span    |||

<br>

|값|의미|기본값|
|---|:---:|---:|
|static| 배치 불가 | 999|
|static| 배치불 | 9999|
|static| 배치불가에요 | 99999|

# 인용문

> 남의 말이나 글에서 직접 따온 문장

> 인용문 작성
>> 중첩 인용문
>>> 중첩 인용문
>>> 중첩 인용문<br>
>>> 중첩 인용문
>>> 중첩 인용문