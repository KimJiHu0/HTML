# grouping

>이번에는 영역을 나누는 방법2가지를 알아갈 시간이다.

- 1. **div를 이용한 영역 나누기**

```html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>html10</title>
   

<!-- 이 부분은 head 태그 안에 작성한 내부 스타일시트  -->
<style type="text/css">
    *{
        padding : 0px;
        margin : 0px;
    }
    div{
        border : 1px dotted blue;
        margin : 10px;
    }
    #body{
        height : 400px;
    }
    #left{
        width : 48%;
        height : 90%;
        float : left;
    }
    #right{
        width : 48%;
        height : 90%;
        float : right;
    }
</style>
</head>
    <body>
        <div id="header">
            <h1>제목</h1>
            <div>
                <span><a href="#">메뉴1</a></span>
                <span><a href="#">메뉴2</a></span>
                <span><a href="#">메뉴3</a></span>
                <span><a href="#">메뉴4</a></span>
            </div>
        </div>
        
        <div id="body">
            <div id="left">
                <p>내용1</p>
            </div>
            <div id="right">
                <p>내용2</p>
            </div>
        </div>
        
        <div id="footer">
            <address>copyright &copy; all rights reserved...</address>
        </div>
    </body>
</html>
```

>grouping 첫번째 방법은 블록 요소인 div Tag를 사용해 그 안에 인라인 요소를 사용하고
>
>공간을 나눠주었다. 이는 html4 일때 이렇게 많이 사용하였다.
>
>head태그 안에 style는 css에서 배울 것이기 때문에 깊게 들어가진 않겠다.
>
>html을 꾸며주는 역할을 한다.

![](https://postfiles.pstatic.net/MjAyMDA2MTRfMTky/MDAxNTkyMDczMjY0MjUx.woZjVMbRxafbwywuKE5ETn54MTD9mgyVSC7SeXczccYg.7ffnPy_hd_gvl2_8KVFF5Bl2XGfJ3NY7IcUHOuUljTAg.PNG.rgusqls/image.png?type=w773)

> 실행결과 화면이다.



```html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>html11</title>

<style type="text/css">
   *{
      padding: 0px;
      margin : 0px;
   }
   .html5{
      border: 1px dotted red;
      margin : 10px;
   }
   section{
      height : 400px;
   }
   #left{
      width : 48%;
      height : 90%;
      float : left;
   }
   #right{
      width :48%;
      height : 90%;
      float: right;
   }

</style>


</head>
<body>

	<header class = "html5">
		<h1>제목</h1>
		<nav class = "html5">
			<span><a href="#">메뉴 1</a></span>
			<span><a href="#">메뉴 2</a></span>
			<span><a href="#">메뉴 3</a></span>
			<span><a href="#">메뉴 4</a></span>
		</nav>
	</header>

	<section class = "html5">
		<article class = "html5" id="left">
			<p>내용 1</p>
			안녕하세요
		</article>
		<article class = "html5" id="right">
			<p>내용 2</p>
		</article>
	</section>
	
	<footer class = "html5">
		<address>copyright &copy; all right reserved...</address>
	</footer>
</body>
</html>
```

> 
>
> 이번 예제는 html5에서 사용하는 공간 나누기다.
>
> html5에서는 시맨틱태그인 [ header, nav, section, article, footer ] 을 사용한다.
>
> html5에서 시맨틱 태그를 사용한 예제도 위의 사진과 똑같은 결과를 출력해낸다.
>
> 시맨틱태그를 사용한 구조를 보여주겠다.

![](https://postfiles.pstatic.net/MjAyMDA2MTRfMTgy/MDAxNTkyMDc0Mjk5MDQw.JVLwuThCiBflQh0KiNeXPQDUqkRihFre2LskA9Rf2Kgg.r6GdJTk4qUSVA8hO1Ej4CAPbEoy3qwgmXwRmss4N1E0g.PNG.rgusqls/image.png?type=w773)

> - header : 주로 머리말, 제목을 표현하기 위해 쓰이는 태그.
> - nav : 콘텐츠를 담고 있는 문서를 사이트간 서로 연결하는 링크 역할을 하는데 '네비게이션'이라고도 불린다. nav는 주로 메뉴에 사용되고 위치에 영향을 받지 않아 어디서든 사용이 가능하다.
> - section : 공간을 나눠주는 콘텐츠 3가지 header section footer 중 하나이다. section은 본문을 담고 있는 태그라고 할 수 있다. section 안에 section을 담을 수 있다.
> - article : section 으로 공간을 나누고 그 안에 article로 실질적인 내용을 넣는다. 예를들면 대분류 안에 내용들을 넣는다고 보면 된다.
> - aside : 사이드바라고 불리고 본문 이외 내용을 담는 시맨틱 태그이다. 주로 본문 옆에 광고 혹은 링크들을 넣어서 사용한다.
> - footer : 홈페이지 맨 밑에 있는 부분을 의미한다. 연락처를 넣고 싶다면 address 태그를 사용하여 표기한다.