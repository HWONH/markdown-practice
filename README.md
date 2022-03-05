# 제목(Header)

<!-- #과 텍스트 사이에 띄어쓰기 권장 -->
# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6
<!-- ------------------------- -->
# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세
<!-- ------------------------- -->
# 줄바꿈(Line Breaks)

<!-- 띄어쓰기 2번 or &lt;br /&gt; 사용 -->
동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려 강산  
대한 사람 대한으로 길이 보전하세
<!-- ------------------------- -->
# 강조(Emphasis)

_이텔릭_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>
<!-- ------------------------- -->
# 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
1. 순서가 필요한 목록

<!-- -과 텍스트 사이에 띄어쓰기 -->
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록 
- 순서가 필요하지 않은 목록
<!-- ------------------------- -->
# 링크(Links)

<a href="https://google.com">GOOGLE</a>

[GOOGLE](https://google.com)

<a href="https://naver.com" title="naver로 이동">NAVER</a>

[NAVER](https://naver.com "naver로 이동")

<!-- MARKDOWN에서 target 속성은 제공하고 있지 않음 -->
<a href="https://naver.com" title="naver로 이동" target="_blank">NAVER</a>  
<!-- ------------------------- -->
# 이미지(Image)

![HEROPY](https://heropy.blog/css/images/logo.png)

<!-- 이미지에 링크 연결 -->
[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog)
<!-- ------------------------- -->
# 인용문(BlockQuota)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어 사전)

> 인용문을 작성하세요!
>> 중첩된 인용문
>>> 중중첩된 인용문 1
>>> 중중첩된 인용문 2
>>> 중중첩된 인용문 3
<!-- ------------------------- -->
# 인라인(Inline) 코드 강조

css에서 `background` 혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.
<!-- ------------------------- -->
# 블록(Block) 코드 강조

```html
<a href="https://naver.com" title="naver로 이동" target="_blank">NAVER</a>  
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

<!-- $는 터미널에 입력되는 코드임을 의미하는 표시이며 실제로는 $ 이후부터 작성한다 -->
```bash
$ git commit =m 'Study Markdown'
```

```plaintext
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세
```
<!-- ------------------------- -->
# 표(Table)

<!-- 
--      기본값;왼쪽 정렬
:--:    가운데 정렬
--:     오른쪽 정렬
 -->

Position 속성

값 | 의미 | 기본값
--|--|:--:
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X
<!-- ------------------------- -->
# 원시 HTML(Raw HTML)
<!-- 마크다운에서 지원되지 않는 문법은 다음과 같이 원시 HTML 문법을 사용하여 작성한다 -->

1. 밑줄 / 줄바꿈
    <!-- <u></u> 대신 <span style="text-decoration: underline;"></span>을 사용하길 권장-->
    동해물과 <u>백두산</u>이 마르고 닳도록<br />하느님이 보우하사 우리나라 만세

1. target 속성  
    <a href="https://naver.com" title="naver로 이동" target="_blank">NAVER</a>

1. width 속성  
    <img width="70" src="https://heropy.blog/css/images/logo.png" alt="HEROPY" />
<!-- ------------------------- -->
# 수평선(Horizontal Rule)

---
***
___