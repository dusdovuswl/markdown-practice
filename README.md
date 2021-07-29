# 제목(Header)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

# 문장(Paragraph)

안녕하세요
안녕히 가세요

# 줄바꿈(Line Breaks)

안녕하세요  
안녕히 가세요  
어서오세요 <br/>
잘 부탁드려요

# 강조(Emphasus)

_이텔릭_  
**두껍게**  
**_이텔릭+두껍게_**  
~~취소선~~  
<u>밑줄</u>

# 목록(List)

1. 순서가 필요한 목록  
1. 순서가 필요한 목록  
1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    1.순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

# 링크(Links)

<a href="http://google.com">GOOGLE</a>

[GOOGLE](http://google.com)

<a href="http://naver.com" title="NAVER로 이동">NAVER</a>

[NAVER](http://naver.com "NAVER로 이동!")

<a href="http://naver.com" title="NAVER로 이동" target="_blank">NAVER</a>

# 이미지(Images)

![]()

![HEROPY](http://heropy.blog/css/images/logo.png)

[![HEROPY](http://heropy.blog/css/images/logo.png)](http://heropy.blog)

# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어 사진)

> 인용문을 작성하세요.
>> 중첩된 인용문
>>> 중첩된 인용문 1
>>>> 중첩된 인용문 2

# 인라인(inline) 코드 강조

css에서 `background` 혹은 `background-image` 속성으로 요소에 배경이미지를 삽입할 수 있습니다.

# 블록(block) 코드 강조

```html
<a href="https://www.google.co.kr/" target="_blank">GOOGLE</a>
```

```css
.list > li {
    position: absolute;
    top: 40px;
}
```

```javascript
function func() {
    var a = 'AAA';
    return a;
}
```

```bash
$ git commit -m 'Study Markdown'
```

```plaintext
안녕하세요
```

# 표(table)

position 속성

값 | 의미 | 기본값
--|:--:|--:
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

# 원시 HTML(Raw HTML)

<u>안녕하세요</u> 안녕하세요<br/>
<span style="text-decoration: underline;">어서오세요</span> 어서오세요

<a href="https://naver.com" title="NAVER로 이동!" target="_blank">NAVER</a>

<img width="70" src="https://heropy.blog/css/images/logo.png" alt="HEROPY" />

# 수평선(Horizontal Rule)

---

***

___