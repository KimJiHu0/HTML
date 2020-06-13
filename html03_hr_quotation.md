# hr Tag, quotation Tag

```
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>html03</title>
</head>
<body>

	<h1>&lt;blockquote&gt;</h1>
	<strong>드래곤 라자</strong> 라는 소설에서, 내가 좋아하는 말이 있습니다.
	<blockquote cite="#" title="드래곤라자 명언">
	<cite>드래곤 라자</cite>
	나는 단수가 아니다.
	</blockquote>
	
	
	<hr/>
	
	<h1>&lt;q&gt;</h1>
	
	<b>드래곤 라자</b> 라는 소설에서, 내가 좋아하는 말이 있습니다.
	<q cite="#" title="드래곤라자 명언">나는 단수가 아니다.</q>
	

</body>
</html>
```

- **(hr)** : 줄을 그어주는 태그이다.

- &lt : " < " 의 의미를 가졌다. 저 태그를 쓰지 않고 " < " 만 쓴다면 html은 속성으로 알아들을 것이다.

- &gt : " > " 의 의미를 가졌다.

  

- **[ 인용문 ]**


  ```
  <h1>&lt;blockquote&gt;</h1>
  <strong>드래곤 라자</strong> 라는 소설에서, 내가 좋아하는 말이 있습니다.
  <blockquote cite="#" title="드래곤라자 명언">
  <cite>드래곤 라자</cite>
  나는 단수가 아니다.
  </blockquote>
  ```

  ​	위의 예제를 보면 blockquote 태그를 사용하였다.

  인용문 중 하나의 태그로 cite Tag인 "드래곤 라자 나는 단수가 아니다."라는 문구의 설명을 속성으로 작성하였다.

  ```
  <hr/>
  
  <h1>&lt;q&gt;</h1>
  
  <b>드래곤 라자</b> 라는 소설에서, 내가 좋아하는 말이 있습니다.
  <q cite="#" title="드래곤라자 명언">나는 단수가 아니다.</q>
  ```

  > ​	이번 예제를 보면 q Tag를 사용한 인용문을 작성하였다.

  >  q Tag는 안에 구문을 "나는 단수가 아니다." 라고 작성하였기 때문에 "" 로 감싸여진 문구가 출력이 된다. 그리고 [ cite="#" title="드래곤라자 명언" ]  을 q Tag 안에 작성하였기 때문에 "나는 단수가 아니다."에 마우스를 올려보면 설명글로 "드래곤라자 명언" 이라는 문구가 출력된다.
  >
  > 하지만 글 안에 ""를 넣기 위해서 q Tag를 사용해선 안된다.

  

  

- cite란 ? 

  >요소(Tag)로 사용할 수도 있고, Tag안에 속성으로 사용할 수도 있다.
  >
  >위의 두 예제를 보면 Tag로 사용한 예제, 속성으로 사용한 예제 둘 다 볼 수 있다.
  >
  >cite는 인용문[ q, blockquote ]에 대한 설명이라고 볼 수 있다.
  
  
  
  실행결과 화면
  
  https://blog.naver.com/rgusqls/221999685120