![header](https://capsule-render.vercel.app/api?section=header)

![header](https://capsule-render.vercel.app/api?type=venom&color=gradient&height=300&section=header&text=Markdown%20-nl-Syntax&animation=fadeIn&fontSize=80&fontAlign=50&stroke=9775fa&fontColor=f3f0ff)

![soft](https://capsule-render.vercel.app/api?type=soft&color=gradient&text=마크업%20문법%20바로가기&fontSize=40&animation=twinkling&descAlignY=50)

---
# 목차
- [마크다운(Markdown)알아보기](##-😃-1.-마크다운(Markdown)-이란?)
- [사용해야 하는 이유](##-🤔-2.-마크다운-문법을-알아야-하는-이유는-무엇일까?)
- [문법 정리](##-📑-3.-마크다운-사용법(문법))


## 😃 1. 마크다운(Markdown) 이란?
마크다운은 텍스트 기반의 ***마크업 언어*** 이다.   
마크다운 문법을 적용하면 일반 텍스트와 동일하게 표시가 가능하다. 


## 🤔 2.마크다운 문법을 알아야 하는 이유는 무엇일까? 

### • 높은 활용도
사람들은 웹사이트, 문서, 노트, 책, 프레젠테이션, 이메일 메시지, 기술 문서 등을 만드는데 마크다운을 사용한다.  

### • 탁월한 접근성
마크다운 형식의 텍스트가 포함된 파일은 거의 모든 애플리케이션을 사용하여 열 수 있다.  

### • 다양한 호환성
마크다운은 플랫폼에 구애받지 않습니다. 모든 운영 체제를 실행하는 모든 기기에서 마크다운 형식의 텍스트를 만들 수 있습니다.  

### • 미래 지향성
마크다운은 앞으로도 지속적으로 사용할 수 있다. 현재 사용 중인 애플리케이션이 나중에 지원이 중단되더라도, 일반 텍스트 편집기를 통해 마크다운 문서를 언제든지 열어볼 수 있다. 이는 책, 학술 논문 등 장기적으로 보존해야 하는 문서를 작성할 때 중요한 장점입니다.

### • 광범위한 지원
마크다운은 Reddit, GitHub과 같은 웹사이트뿐만 아니라 다양한 데스크톱 및 웹 기반 애플리케이션에서도 널리 사용됩니다.
 

|       💪 장점        |          🤨 단점          |
| :-----------------: |:------------------------:|
|         간결성        |         표준이 없음         |
| 별도의 도구없이 작성 가능 | 도구에 따라 변환방식,표시가 다름 |
|  다양한 형태로 변환 가능  |   모든 HTML 마크업 대체 불가  |
|      용량 차지 少      |                          |
|      버전 관리 가능     |                          |
|    다양한 플랫폼 지원    |                          |
|     장기적 보존 가능     |                          |
|    다양한 플랫폼 지원    |                          |
|    다양한 플랫폼 지원    |                          |
|    다양한 플랫폼 지원    |                          |


## 📑 3. 마크다운 사용법(문법)
### 3.1. 헤더 (Headers)
* 큰 제목: 문서 제목  
```
# H1 제목
```
  # H1 제목

* 작은 제목: 문서 부제목  
```
H2 제목
```
  ## H2 제목
---

* 글머리: H1~H6까지 지원
```
# H1 제목
## H2 제목
### H3 제목
#### H4 제목
##### H5 제목
###### H6 제목
```
# H1 제목
## H2 제목
### H3 제목
#### H4 제목
##### H5 제목
###### H6 제목
####### H7 제목 (지원하지 않음)

---

## 3.2. 인용 블록 (Block Quote)
이메일에서 사용하는 ```>``` 블럭인용문자를 이용한다.
```
> 인용 블록 하나 사용. 
>	> 인용 블록 두 개 사용.
>	>	> 인용 블록 세 개 사용.
```
> 인용 블록 하나 사용. 
>	> 인용 블록 두 개 사용.
>	>	> 인용 블록 세 개 사용.

이 안에서는 다른 마크다운 요소를 포함할 수 있다.
> ### H3 제목
> * 리스트
>	```
>	코드
>	```

### 3.3. 목록
### ● 순서있는 목록(번호)
순서있는 목록은 숫자와 점을 사용한다.

1. 첫 번째
2. 두 번째
3. 세 번째

```
//이렇게 작성해도
1. 첫 번째
3. 세 번째
2. 두 번째
```
표시는 내림차순으로 적용이 된다. 
1. 첫 번째
3. 세 번째
2. 두 번째

### ● 순서없는 목록(글머리 기호: `*`, `+`, `-` 지원)
**같은 기호여도 순서에 따라 표시가 달라진다. 🔴 > ⭕️ > 🟥 > 🟥 > 🟥**
```
* 빨강
  * 주황
    * 노랑
      * 초록
        * 파랑
        
```
* 빨강
  * 주황
    * 노랑
      * 초록
        * 파랑
```
+ 빨강
  + 주황
    + 노랑
      + 초록
        + 파랑
```
+ 빨강
  + 주황
    + 노랑
      + 초록
        + 파랑
```
- 빨강
  - 주황
    - 노랑
      - 초록
        - 파랑
```
- 빨강
  - 주황
    - 노랑
      - 초록
        - 파랑

## 3.4. 코드
***(기본 에디터 텝 간격 설정을 4로 설정한 경우)***  
4개의 공백 또는 하나의 탭으로 들여쓰기는 줄과 줄 사이에서 단독으로 내용이 있을 때만 들여쓰기가 가능하다. 

### 3.4.1. 들여쓰기
```
//아래 내용을 그대로 복사 후

들여쓰기는 단순한 공백이 아니라, 
  문장의 깊이를 더하고 
가독성을 높이는 작은 배려이다.
```

적용해보면, 아래 적용이 되지 않는 것을 볼 수 있다. 

들여쓰기는 단순한 공백이 아니라, 
  문장의 깊이를 더하고 
가독성을 높이는 작은 배려이다.
---

> 단독으로 구분하여 사용하지 않으면 인식이 되지 않는 문제가 생긴다. 

******
This is a normal paragraph:
    This is a code block.
end code block.
*****

Here is a simple flow chart:

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

### 3.4.1. 코드블럭
코드블럭은 다음과 같이 2가지 방식을 사용할 수 있습니다:

* `<pre><code>{code}</code></pre>` 이용방식

```
<pre>
<code>
public class BootSpringBootApplication {
  public static void main(String[] args) {
    System.out.println("Hello, Honeymon");
  }

}
</code>
</pre>
```

<pre>
<code>
public class BootSpringBootApplication {
  public static void main(String[] args) {
    System.out.println("Hello, Honeymon");
  }
}
</code>
</pre>

* 코드블럭코드("\```") 을 이용하는 방법

<pre>
<code>
```
public class BootSpringBootApplication {
  public static void main(String[] args) {
    System.out.println("Hello, Honeymon");
  }
}
```
</code>
</pre>

```
public class BootSpringBootApplication {
  public static void main(String[] args) {
    System.out.println("Hello, Honeymon");
  }
}
```

**깃헙**에서는 코드블럭코드("\```") 시작점에 사용하는 언어를 선언하여 [문법강조(Syntax highlighting)](https://docs.github.com/en/github/writing-on-github/creating-and-highlighting-code-blocks#syntax-highlighting)이 가능하다.

<pre>
<code>
```java
public class BootSpringBootApplication {
  public static void main(String[] args) {
    System.out.println("Hello, Honeymon");
  }
}
```
</code>
</pre>

```java
public class BootSpringBootApplication {
  public static void main(String[] args) {
    System.out.println("Hello, Honeymon");
  }
}
```


## 3.5. 수평선 ```<hr/>```
아래 줄은 모두 수평선을 만든다. 마크다운 문서를 미리보기로 출력할 때 *페이지 나누기* 용도로 많이 사용한다.

```
* * *

***

*****

- - -

---------------------------------------
```

* 적용예
* * *

***

*****

- - -

---------------------------------------


## 3.6. 링크
* 참조링크

```
[link keyword][id]

[id]: URL "Optional Title here"

// code
Link: [Google][googlelink]

[googlelink]: https://google.com "Go google"
```

Link: [Google][googlelink]

[googlelink]: https://google.com "Go google"

* 외부링크
```
사용문법: [Title](link)
적용예: [Google](https://google.com, "google link")
```
Link: [Google](https://google.com, "google link")

* 자동연결
```
일반적인 URL 혹은 이메일주소인 경우 적절한 형식으로 링크를 형성한다.

* 외부링크: <http://example.com/>
* 이메일링크: <address@example.com>
```

* 외부링크: <http://example.com/>
* 이메일링크: <address@example.com>

## 3.7. 강조
```
*single asterisks*
_single underscores_
**double asterisks**
__double underscores__
~~cancelline~~
```

* *single asterisks*
* _single underscores_
* **double asterisks**
* __double underscores__
* ~~cancelline~~

> ```문장 중간에 사용할 경우에는 **띄어쓰기** 를 사용하는 것이 좋다.```   
> 문장 중간에 사용할 경우에는 띄어쓰기를 사용하는 것이 좋다.


## 3.8. 이미지
```
![Alt text](/path/to/img.jpg)
![Alt text](/path/to/img.jpg "Optional title")
```
![석촌호수 러버덕](http://cfile6.uf.tistory.com/image/2426E646543C9B4532C7B0)
![석촌호수 러버덕](http://cfile6.uf.tistory.com/image/2426E646543C9B4532C7B0 "RubberDuck")

사이즈 조절 기능은 없기 때문에 ```<img width="" height=""></img>```를 이용한다.

예
```
<img src="/path/to/img.jpg" width="450px" height="300px" title="px(픽셀) 크기 설정" alt="RubberDuck"></img><br/>
<img src="/path/to/img.jpg" width="40%" height="30%" title="px(픽셀) 크기 설정" alt="RubberDuck"></img>
```

<img src="http://cfile6.uf.tistory.com/image/2426E646543C9B4532C7B0" width="450px" height="300px" title="px(픽셀) 크기 설정" alt="RubberDuck"></img><br/>
<img src="http://cfile6.uf.tistory.com/image/2426E646543C9B4532C7B0" width="40%" height="30%" title="%(비율) 크기 설정" alt="RubberDuck"></img>

## 3.9. 줄바꿈
3칸 이상 띄어쓰기(` `)를 하면 줄이 바뀐다.

```
* 줄 바꿈을 하기 위해서는 문장 마지막에서 3칸이상을 띄어쓰기해야 한다. 
이렇게

* 줄 바꿈을 하기 위해서는 문장 마지막에서 3칸이상을 띄어쓰기해야 한다.___\\ 띄어쓰기
이렇게
```

* 줄 바꿈을 하기 위해서는 문장 마지막에서 3칸이상을 띄어쓰기해야 한다. 이렇게

* 줄 바꿈을 하기 위해서는 문장 마지막에서 3칸이상을 띄어쓰기해야 한다.    \
이렇게


![footer](https://capsule-render.vercel.app/api?section=footer)