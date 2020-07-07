## HTML

html 이란? hyper text markup language

웹사이트에서 각 요소가 무엇을 뜻하는지 알려주는 언어

tag를 이용하여 작성한다!!

HTML은 태그덩어리!!



### HTML tag 작성

`index.html`

왜 index인가?

웹 서버들이 index 파일을 제일 먼저 찾도록 설계되어 있다. default

태그는 어떻게 생겼는가??

<이름 속성="값"> 내용 </이름>

```html
<name attribute="value">Content</name> 
<!-- 위는 예시 -->

<title>This is the title of the document</title>
<a href="http://google.com" target="blank">Go to google</a>
<!-- blank 옵션은 새창에서... -->
```



### HTML 문서 만들기



```HTML
<!DOCTYPE html> 
<!-- 브라우저로 하여금 이 문서가 html 문서임을 알려준다. 
    <html> </html>으로 열고 닫을 수 있다.
    <!DOCTYPE html>은 self-contained 태그. 즉 혼자 열고 닫는 태그이다.
    그 자체로 정보를 제공하기 때문...
-->



<html>
<!-- 문서는 크게 두개로 나눌 수 있는데, head와 body 
head는 유저에게 보이지 않는다. 브라우저에게 웹사이트에 관한 정보를 제공하는 곳.
body는 사람들이 읽는 컨텐츠를 제공하는 곳.
-->
  <head>
      <title>This is my title</title>
      <!-- 브라우저의 제목 -->
  </head>
  <body>
    <h1>This is my big title</h1>
    <h6>This is my small title</h6>
     <!-- 큰 제목을 쓰고 싶을 때 h1 h6이 가장 작다. -->
  </body>
</html>

```

