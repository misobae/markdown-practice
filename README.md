# 제목(Header) 

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

# 문장(Paragraph)
문장입니다~  
띄어쓰기 두번 하면 줄바꿈이  
됩니다 <br />
br태그도 먹습니다. 원시 HTML

# 강조(Emphasis)
_이텔릭_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선 물결표시는 영어로 Tild~~  
<u>밑줄</u>

# 목록(List)
1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 숫자를 직접 1, 2, 3 넣지 않아도 알아서 숫자가 입력된다
   1. 스페이스 두번 들여쓰기
   1. ㅇ

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
  - 순서가 필요하지 않은 목록

# 링크(Link)
<a href="https://google.com" title="구글로 이동!" target="_blank">GOOGLE</a>  
[GOOGLE](https://google.com "구글로 이동!") 
마크다운은 새창으로 이동 문법을 지원하지 않음. 원시 HTML로 작성하기

# 이미지(Images)
![Starbucks](https://peaceful-torvalds-63c123.netlify.app/images/starbucks_logo.png)  

[![Starbucks](https://peaceful-torvalds-63c123.netlify.app/images/starbucks_logo.png)](https://peaceful-torvalds-63c123.netlify.app/index.html)
이미지 + 링크

# 인용문(BlockQuote)
> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  

> 인용문
>> 인용문 중첩
>>> 인용문 중중첩

# 인라인(Inline) 코드 강조
CSS에서 `background` 혹은
`background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

# 블록(block) 코드 강조
```html
<a href="https://google.com" title="구글로 이동!" target="_blank">GOOGLE</a>  
```

```css
.css {display: block;}
```

```javascript
function google(){
  const a = 'a'
  return a;
}
```

```bash
$ git commit -m 'study markdown'
```

```plaintext
텍스트 강조
```

# 표(Table)
position 속성

값 | 의미 | 기본값  
--|--:|:--:
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

# 원시 HTML(Raw HTML)

동해물과 <span style="text-decoration: underline;">백두산</span>이 마르고 닳도록<br />
하느님이 보우하사 우리나라 만세

# 수평선(Horizontal Rule)
---

***

___