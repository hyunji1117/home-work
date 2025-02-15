![header](https://capsule-render.vercel.app/api?section=header)

![header](https://capsule-render.vercel.app/api?type=venom&color=gradient&width=100%&height=200&section=header&text=Markdown%20-nl-Syntax&animation=fadeIn&fontSize=80&fontAlign=50&stroke=9775fa&fontColor=f3f0ff)

[<img src="https://capsule-render.vercel.app/api?type=soft&color=gradient&text=마크업%20문법%20바로가기&fontSize=40&animation=twinkling&descAlignY=50&height=100"/>](#3-마크다운-사용법문법)

# 😃 1. 마크다운(Markdown) 이란?
마크다운은 규칙을 기반으로 일반 텍스트를 구조화 된 문서로 작성하기 위한 ***마크업 언어*** 이다. 

# 🤔 2.왜 마크다운을 사용해야 할까?
## • 다양한 활용도
웹사이트, 문서, 노트, 책, 프레젠테이션, 이메일 메시지, 기술 문서 등을 작성하는데 마크다운을 사용한다. 

## • 높은 가독성
마크다운 형식의 문서는 태그나 서식 지정 지침이 있어 마크업 처럼 보이지 않고 일반 텍스트 그대로 보이는 특징이 있다. 

## • 쉬운 접근성
마크다운 형식의 텍스트가 포함된 파일은 거의 모든 애플리케이션을 사용하여 열 수 있으며 일반 텍스트 작성과 비슷하게 작성이 쉽다. 

## • 열린 호환성
마크다운은 플랫폼에 구애받지 않습니다. 모든 운영 체제를 실행하는 모든 기기에서 마크다운 형식의 텍스트를 만들 수 있습니다.  

## • 미래 지향성
마크다운은 앞으로도 지속적으로 사용할 수 있다. 현재 사용 중인 애플리케이션이 나중에 지원이 중단되더라도, 일반 텍스트 편집기를 통해 마크다운 문서를 언제든지 열어볼 수 있다. 이는 책, 학술 논문 등 장기적으로 보존해야 하는 문서를 작성할 때 중요한 장점입니다.  


|       💪 장점        |          🤨 단점          |
| :-----------------: |:------------------------:|
|         간결성        |         표준이 없음         |
| 별도의 도구없이 작성 가능 | 도구에 따라 변환방식,표시가 다름 |
|  다양한 형태로 변환 가능  |   모든 HTML 마크업 대체 불가  |
|      용량 차지 少      |                          |
|      버전 관리 가능     |                          |
|    다양한 플랫폼 지원    |                          |
|  장기적 데이터 보존 가능  |                          |

# 3. 마크다운 사용법(문법)
## 3.1. 헤더 (Headers)

> H1~H6까지 지원
```bash
✅ 작성 방법: 

# H1 제목
## H2 제목
### H3 제목
#### H4 제목
##### H5 제목
###### H6 제목
####### H7 제목 (지원하지 않음)
```
> 🔽 보여지는 모습
# H1 제목
## H2 제목
### H3 제목
#### H4 제목
##### H5 제목
###### H6 제목
####### H7 제목 (지원하지 않음)

---

## 3.2. 굵은 글씨 (Bold)
```bash
✅ 작성 방법: 

**강조**하고 싶은 단어에 표시.
```
> 🔽 보여지는 모습

**강조**하고 싶은 단어에 표시.

---

## 3.3. 기울여 쓰기 (italic)
```bash
✅ 작성 방법: 

*기울여* 써볼까요? 
```
> 🔽 보여지는 모습

*기울여* 써볼까요? 

---

## 3.4. 취소선 (Strikethrough)
```bash
✅ 작성 방법: 

📢 지금 한정 할인!
~~₩99,000~~ → ₩49,000 (50% OFF!) 🏷️
```
> 🔽 보여지는 모습

📢 지금 한정 할인!  
~~₩99,000~~ → ₩49,000 (50% OFF!) 🏷️

---

## 3.5. 인용 블록 (Block Quote)
> 이메일에서 사용하는 ```>``` 블럭 인용문자를 사용한다.
```bash
✅ 작성 방법: 

> 인용 블록 하나 사용. 
>> 인용 블록 두 개 사용.
>>> 인용 블록 세 개 사용.
```
```
🔽 보여지는 모습
```
> 인용 블록 하나 사용. 
>> 인용 블록 두 개 사용.
>>> 인용 블록 세 개 사용.

```
이 안에서는 다른 마크다운 요소를 포함할 수 있다.
```
> ### H3 제목
> * 리스트
>	```
>	코드
>	```

## 3.6. 목록
### ● 순서있는 목록(번호)
순서있는 목록은 숫자와 점을 사용한다.

```bash
✅ 작성 방법: 

1. 첫 번째
2. 두 번째
3. 세 번째
```

> 🔽 보여지는 모습
1. 첫 번째
2. 두 번째
3. 세 번째

```
✅ 이렇게 작성해도

1. 첫 번째
3. 세 번째
2. 두 번째
```
> 🔽 표시는 내림차순으로 적용이 된다. 
1. 첫 번째
3. 세 번째
2. 두 번째

---

### ● 순서없는 목록(글머리 기호: `*`, `+`, `-` 지원)
**같은 기호여도 순서에 따라 표시가 달라진다. 🔴 > ⭕️ > 🟥 > 🟥 > 🟥**
```bash
✅ 작성 방법: 

* 빨강
  * 주황
    * 노랑
      * 초록
        * 파랑
        
```
> 🔽 보여지는 모습
* 빨강
  * 주황
    * 노랑
      * 초록
        * 파랑
```
✅ 작성 방법:

+ 빨강
  + 주황
    + 노랑
      + 초록
        + 파랑
```
> 🔽 보여지는 모습
+ 빨강
  + 주황
    + 노랑
      + 초록
        + 파랑
```
✅ 작성 방법:

- 빨강
  - 주황
    - 노랑
      - 초록
        - 파랑
```
> 🔽 보여지는 모습
- 빨강
  - 주황
    - 노랑
      - 초록
        - 파랑

## 3.7 코드블럭
> 코드블럭은 2가지 방식을 사용할 수 있다. 

```bash
✅ 작성 방법1: 

`코드 위치`를 백틱(Backtick)으로 감싼다. 
```
> 🔽 보여지는 모습

`코드 위치`를 백틱(Backtick)으로 감싼다. 

> **깃헙**에서는 코드블럭코드("```") 시작점에 사용하는 언어를 선언하여 [문법강조(Syntax highlighting)](https://docs.github.com/en/github/writing-on-github/creating-and-highlighting-code-blocks#syntax-highlighting)이 가능하다.

<pre>
<code>
✅ 작성 방법2: 

```javascript
function greet(name) {
    console.log(`Hello, ${name}!`);
}
greet("Markdown");
```
</pre>
</code>

> 🔽 보여지는 모습

```javascript
function greet(name) {
    console.log(`Hello, ${name}!`);
}
greet("Markdown");
```

---

## 3.8. 수평선 ```<hr/>```
> 아래 줄 모두 수평선을 만든다. 마크다운 문서를 미리보기로 출력할 때 *페이지 나누기* 용도로 많이 사용한다.

```bash
✅ 작성 방법:

* * *

***

*****

- - -

---------------------------------------
```

> 🔽 보여지는 모습
* * *

***

*****

- - -

---------------------------------------

## 3.9. 링크
* 참조링크

```bash
✅ 작성 방법:

[link keyword][id]

[id]: URL "Optional Title here"

// code
Link: [Google][googlelink]

[googlelink]: https://google.com "Go google"
```

> 🔽 보여지는 모습

Link: [Google][googlelink]

---

[googlelink]: https://google.com "Go google"

* 외부링크
```bash
✅ 작성 방법:

사용문법: [Title](link)
적용예: [Google](https://google.com, "google link")
```
> 🔽 보여지는 모습

Link: [Google](https://google.com, "google link")

---

* 자동연결
> 일반적인 URL 혹은 이메일주소인 경우 적절한 형식으로 링크를 형성한다.
```bash
✅ 작성 방법:

* 외부링크: <http://example.com/>
* 이메일링크: <address@example.com>
```
> 🔽 보여지는 모습
* 외부링크: <http://example.com/>
* 이메일링크: <address@example.com>

---

## 4.0. 이미지
> 모든 환경에서 동일한 방식으로 동작하기 위해 이미지 경로는 ***절대경로*** 로 작성한다. 
```bash
✅ 작성 방법:

![Alt text](/path/to/img.jpg)
![Alt text](/path/to/img.jpg "Optional title")
```
> 🔽 보여지는 모습

![코딩하는 토끼](/src/assets/images/coding-rabbit.webp)
![코딩하는 토끼](/src/assets/images/coding-rabbit.webp "CodingRabbit")

---

## 4.1. 괄호 (` `)

```bash
✅ 작성 방법:

(` `)
```
> 🔽 보여지는 모습

(` `)

---

## 4.2. 줄바꿈 
### 4.2.1 공백 두 칸(␣␣)을 활용한 줄바꿈

```bash
✅ 작성 방법:

내일의 나는 오늘보다 더 강하다!🔥␣␣
오늘 흘린 땀과 눈물은 내일의 나를 빛나게 한다!

```
> 🔽 보여지는 모습

내일의 나는 오늘보다 더 강하다!🔥  
오늘 흘린 땀과 눈물은 내일의 나를 빛나게 한다!

---

### 4.2.2 <br> 태그를 활용한 줄바꿈

```bash
✅ 작성 방법:

내일의 나는 오늘보다 더 강하다!🔥<br />
오늘 흘린 땀과 눈물은 내일의 나를 빛나게 한다!

```
> 🔽 보여지는 모습

내일의 나는 오늘보다 더 강하다!🔥<br />
오늘 흘린 땀과 눈물은 내일의 나를 빛나게 한다!

---

### 4.2.3 역슬래시(\) 를 이용하면 줄바꿈

```bash
✅ 작성 방법:

내일의 나는 오늘보다 더 강하다!🔥\
오늘 흘린 땀과 눈물은 내일의 나를 빛나게 한다!

```
> 🔽 보여지는 모습

내일의 나는 오늘보다 더 강하다!🔥\
오늘 흘린 땀과 눈물은 내일의 나를 빛나게 한다!

---
## 4.3. 표
### 4.3.1 테이블 표
```bash
✅ 작성 방법:

|  구문(Syntax)  |  설명(Description)  |
|  -----------: |  ----------------  |
|  헤더(Header)  |     제목(Title)     |
| 단락(Paragraph)|     본문(Text)      |
```

> 🔽 보여지는 모습 (우측에 :세미콜론 추가하면 우정렬 가능)

|  구문(Syntax)  |  설명(Description)  |
|  -----------: |  ----------------  |
|  헤더(Header)  |     제목(Title)     |
| 단락(Paragraph)|     본문(Text)      |

---
### 4.3.2 Mermaid 다이어그램 (Mermaid diagrams)
<pre>
<code>
✅ 작성 방법:

단순한 순서도:
```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
</code>
</pre>

> 🔽 보여지는 모습
아래는 간단한 순서도 이다. 
```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

## 4.4. 각주 (footnote) - github 미지원
```bash
✅ 작성 방법:

Markdown은 간단하고 직관적인 마크업 언어입니다.[^1]  
누구나 쉽게 배울 수 있으며, 다양한 플랫폼에서 사용됩니다.[^참고]

[^1]: John Gruber가 개발한 텍스트 기반 마크업 언어.  
[^참고]: GitHub, Notion, Wiki 등에서 널리 사용됨.
```

> 🔽 보여지는 모습

Markdown은 간단하고 직관적인 마크업 언어입니다.[^1]  
누구나 쉽게 배울 수 있으며, 다양한 플랫폼에서 사용됩니다.[^참고]

[^1]: John Gruber가 개발한 텍스트 기반 마크업 언어.  
[^참고]: GitHub, Notion, Wiki 등에서 널리 사용됨.

> **페이지 하단에서 출력 확인**
---

## 4.5. 수학 표기
### 4.5.1 위 첨자 (Superscript)
```bash
✅ 작성 방법:

X<sup>2</sup>
```

> 🔽 보여지는 모습

X<sup>2</sup>

---
### 4.5.2 아래 첨자 (Subscript)
```bash
✅ 작성 방법:

H<sub>2</sub>O
```

> 🔽 보여지는 모습

H<sub>2</sub>O

---

## 참고자료
- [Working with advanced formatting](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting)
- [Extended Syntax](https://www.markdownguide.org/extended-syntax/#subscript)

![footer](https://capsule-render.vercel.app/api?section=footer)