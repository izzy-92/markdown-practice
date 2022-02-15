# 제목(Header)

# 제목 1 띄어쓰기 권장
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6


# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리 나라 만세

# 줄바꿈 (Line Breaks)

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려 강산<br/>
대한 사람 대한으로 길이 보전하세

# 강조(Emphasis)

_이텔릭_ : 언더바를 앞뒤로 2번쓰면 사이의 글자가 기울어진다.

**두껍게**  : ** 앞뒤로 입력하면 글자가 두꺼워짐 

**_이텔릭 + 두껍게_**  : 이텔릭과 글자두꺼운 효과를 두개 동시 사용하는 방법.  

~~취소선~~ : 물결 앞뒤로 2개 표시  

<u>밑줄</u>  : u태그를 사용하여 밑줄 표시.

# 목록(List)

1. 순서가 필요한 목록 
1. 순서가 필요한 목록 2번
1. 순서대로 3번이 자동으로 들어간다!
    1. 들여쓰기 2번을 하니 3번 하위에 새로운 1번 목록이 만들어졌다.
    1. 순서가 필요한 목록
1. 순서가 필요한 목록 


- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록 들여쓰기 두번
    - 순서가 필요하지 않은 목록 서브목록 생성
- 순서가 필요하지 않은 목록

# 링크(Links)
// 기존 a태그 형태  
<a href="https://google.com">GOOGLE</a> 

// 마크다운 문법형태  
[GOOGLE](https://google.com)

// 타이틀 추가 (기존방법)  
<a href="https://naver.com" title="네이버로이동!">NAVER</a> 

// 타이틀 추가 (마크다운 방법)  
[NAVER](https://naver.com "네이버로 이동!")

// 새탭 열기 (마크다운에서는 제공하고있지않음)  
<a href="https://daum.net" title="다음으로 이동!" target="_blank">Daum</a>  

# 이미지(Images)  
![HEROPY](https://heropy.blog/css/images/logo.png)  
링크와의 차이는 맨 앞에 느낌표가 들어있으면  
[대체텍스트]와 (이미지경로)로 이미지가 출력된다.

[![HEROPY](https://heropy.blog/css/images/logo.png)](https://daum.net)
이미지 클릭하면 다음주소 경로로 이동한다.

# 인용문 (BlockQuote)
> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.
첫번째로 맨 앞에 꺽쇠기호와 띄어쓰기를 넣는다.

> 인용문을 작성하세요!
>> 중첩된 인용문
>>> 중중첩된 인용문 1  
>>> 중중첩된 인용문 2  
>>> 중중첩된 인용문 3  

# 인라인 (inline) 코드 강조
CSS에서 `background` 혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.
(벡틱``기호 사용, 하나의 코드가 된다.)

# 블록(block) 코드 강조
```html
<a href="https://daum.net" target="_blank">Daum</a>
```
앞 뒤로 벡틱기호 3번(```)을 사용해주면 블록코드로 하이라이팅해서 사용할수있다. (html, css, javascript 모두 동일)   

```css
.list > li {
  position: absolute;
  top: 40px;
}
```

```javascript
function: func() {
  var a = 'AAA';
  return a;
}
```
혹은 터미널에다가 git이라는 명령어를 통해서  버전관리를 할수있었는데 이 명령코드도 블록코드로 강조하여 명시할수있다.

```bash
$ git commit - m 'Study Markdown'
```

```plaintext
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리 나라 만세
```

# 표 (Table)

position 속성
정렬은 콜론(:)기호로, 표는 | 로

값 | 의미 | 기본값  
--|:--:|--:  
static | 기준 없음 | O  
relative | 요소 자신 | X  
absolute | 위치상 부모요소 | X
fixed | 뷰포트 | X

# 원시 HTML (Raw HTML)
: 마크다운 문법안에서 실제 html 문법을 사용하는 개념.  

u태그 대신 span 태그로  
특정한 단어, 문장 묶어서 스타일 넣어주는것을 권장.

동해물과 <span style="text-decoration: underline;">백두산</span>이 마르고 닳도록<br/>
하느님이 보우하사 우리나라 만세

<a href="https://daum.net" title="다음으로 이동!" target="_blank">Daum</a>  

---

<img width="70" src="https://heropy.blog/css/images/logo.png" alt="HEROPY">

# 수평선(Horizontal Rule)

---

***
___