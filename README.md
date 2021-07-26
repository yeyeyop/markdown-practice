# 제목(Header)

# 제목 1
## 제목 2
### 제목 3
##### 제목 5
###### 제목 6

# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록
우리나라 만세

# 줄바꿈(Line Breaks): 띄어쓰기 2번/<'br>태그

동해물과 백두산이 마르고 닳도록  
우리나라 만세

# 강조(Emphasis)

일반  
_이텔릭_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>

# 목록(List)
1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록  
   1. 순서가 필요한 목록
   1. 순서가 필요한 목록
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

<a href="http://naver.com" title="NAVER로 이동!">NAVER</a>   
[NAVER](http://naver.com "NAVER로 이동!")

# 이미지(Image)

![puppy](https://image.dongascience.com/Photo/2020/03/5bddba7b6574b95d37b6079c199d7101.jpg)

[![puppy](https://image.dongascience.com/Photo/2020/03/5bddba7b6574b95d37b6079c199d7101.jpg)](http://naver.com)

# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어 사전)

>인용문을 작성하세요!
>>중첩된 인용문
>>> 중첩된 인용문 1  
>>> 중첩된 인용문 2  
>>> 중첩된 인용문 3

# 인라인 코드(inline) 강조

CSS에서 `background` 혹은 
`background-image` 속성으로 요소에 배경
이미지를 삽입할 수 있습니다.

# 블록(block)코드 강조

```html
<a href="http://www.google.co.kr/" target="_blank">GOOGLE</a>
```

```css
.list > li {
    position: absolute;
    top:40px;
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
동해물과 백두산이 마르고 닳도록
```

# 표(Table)

position 속성

값 | 의미 | 기본값
--|:--:|--:
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X 
  
# 원시 HTML(Raw HTML)

<span style="text-decoration: underline;">동해물</span>과 <u>백두산</u>이 마르고 닳도록<br />
우리나라 만세

<a href="http://naver.com" title="NAVER로 이동!" target="_blank">NAVER</a>   

---  
  
<img width="70" src="https://image.dongascience.com/Photo/2020/03/5bddba7b6574b95d37b6079c199d7101.jpg" alt="puppy">

# 수평선(Horizontal Rule)

---

***

___