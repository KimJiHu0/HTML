> 블록요소, 인라인요소



``` 
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Insert title here</title>
</head>
<body>

	<q>
		<h2 style="background-color: pink;">블록 요소</h2>
	</q>

	<p>줄바꿈</p>
	<div>
		블록요소 안에 텍스트, <strong>인라인 요소</strong> 포함가능.
		<p>블록요소 안에 블록요소 포함가능</p>
	</div>

	<hr />

	<h2>인라인 요소</h2>
	<a href="#">줄바꿈 x</a>
	<!-- 줄바꿈 태그 <br/> -->
	<q style="background-color: skyblue;"> 인라인 요소 안에 텍스트와<a>인라인 요소</a>
		포함가능
	</q>
	<span>인라인 요소 안에
		<p>블록 요소</p> 포함불가
	</span>
	<!-- 사용은 가능하나, 웬만하면 쓰지말자. -->

</body>
</html>
```

> - 블록요소
>
>   블록 요소 안에는 인라인 요소를 포함할 수 있다. (<div> 안에 <p>태그를 사용할 수 있다.)
>
>   블록 요소는 커다란 공간을 가지고 있다.
>
>   
>
> - 인라인요소
>
>   인라인 요소 안에는 인라인 요소를 포함할 수 있지만 블록 요소를 포함할 수 없다.
>
>   [ 사실 html5에서는 포함할 수 있지만 웬만해서는 하지 않는게 좋다. ]
>   
>   인라인 요소는 자신의 크기만큼의 공간을 가지고 있다.

![image-20200613175051130](C:\Users\rgusq\AppData\Roaming\Typora\typora-user-images\image-20200613175051130.png)