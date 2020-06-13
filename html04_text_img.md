# html text, img

```
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>html04</title>
</head>
<body>

	<h1>Text</h1>
	
	<p>
		<b>진하게(&lt;b&gt;)</b>
		<strong>진하게(&lt;strong&gt;)</strong></br>
		<em>기울임(&lt;em&gt;)</em></br>
		<i>기울임(&lt;i&gt;)</i></br>
		<small>작은 텍스트 표시, (&lt;small&gt;)</small>코멘트<br/>
		윗<sup>첨자</sup>(&lt;sup&gt;)</br>
		아래<sub>첨자</sub>(&lt;sub&gt;)</br>
		<ins>내용 추가(&lt;ins&gt;)</ins></br>
		<del>내용 삭제(&lt;del&gt;)</del></br>
	</p>
	
	<hr/>
	<h1>img00</h1>
	<img alt="여자친구"src="img/img00.jpg" width="300px" height="200px"/>
	<!-- alt는 그림이 안나올 때 그림에 대한 설명, src는 파일의 해당 경로. -->
	<!-- WebContent : 프로젝트 가장 기본폴더 [http://localhost:8787/UI01_HTML/] context root-->
	<!-- gui : 그래픽유아이  / cil : 캐릭터 -->
	<!-- / : 최상위  |  ./ : 현재폴더   |  ../ : 상위폴더 -->
	<!-- width는 가로 hegiht는 세로 -->
	<!-- px : 픽셀(해상도 별 상대크기)
		 pt : 포인트 ( 1pt = 약 0.72cm )
		 %,em,rem, : 지정/상속 등에 대한 백분율 (상대크기)
	 -->
	 
	 <h3>이미지에 링크 걸기</h3>
	 <a href="index.html" title="go index!!">
	 <img alt="test" src="img/img00.jpg" width="100px" height="100px"/>
	 </a>
	 
	 <h3>이미지 맵</h3>
	  <img alt="test" src="img/img00.jpg" width="100px" height="100px" usemap="#my"/>
	  <map name="my">
	  	<area alt="" shape="rect" coords="25,25,75,75" href="index.html" title="가즈아 인덱스"/>
	  </map>

</body>
</html>
```



- **텍스트에 사용되는 Tag들**

  b : b Tag 안에 작성한 문구의 글씨를 진하게 만들어주는 Tag

  strong : strong Tag 안에 작성한 문구의 글씨를 진하게 만들어주는 Tag

  em : em Tag 안에 작성한 문구의 글씨를 기울여주는 Tag

  i : i Tag 안에 작성한 문구의 글씨를 기울여주는 Tag

  small : small Tag 안에 작성한 문구의 글씨를 작은글씨로 만들어주는 Tag

  sup : 윗첨자 Tag

  sub : 아랫첨자 Tag

  ins : 내용추가 Tag

  del : 내용 삭제 Tag

  ```
  		<b>진하게(&lt;b&gt;)</b>
  		<strong>진하게(&lt;strong&gt;)</strong></br>
  		<em>기울임(&lt;em&gt;)</em></br>
  		<i>기울임(&lt;i&gt;)</i></br>
  		<small>작은 텍스트 표시, (&lt;small&gt;)</small>코멘트<br/>
  		윗<sup>첨자</sup>(&lt;sup&gt;)</br>
  		아래<sub>첨자</sub>(&lt;sub&gt;)</br>
  		<ins>내용 추가(&lt;ins&gt;)</ins></br>
  		<del>내용 삭제(&lt;del&gt;)</del></br>
  ```

  https://blog.naver.com/PostView.nhn?blogId=rgusqls&Redirect=View&logNo=221999685120&categoryNo=14&isAfterWrite=true#

  

- **img Tag**

  alt : 이미지가 나오지 않을 경우 설명해주는 속성.

  src : 이미지가 있는 경로를 작성하는 속성.

  width : 가로 길이 속성. px 혹은 %를 붙여 작성한다.

  height : 세로 길이 속성. px 혹은 %를 붙여 작성한다. 

  ```
  <img alt="여자친구"src="img/img00.jpg" width="300px" height="200px"/>
  ```

  

  

- **img에 링크걸기**

  **1.이미지에 링크걸기**

  ​	a : 링크를 걸어주는 Tag이다.

  ```
  	 <a href="index.html" title="go index!!">
  	 <img alt="test" src="img/img00.jpg" width="100px" height="100px"/>
  	 </a>
  ```

  

  ​	

  **2.이미지 맵**

  ​	위의 예제와 같이 링크를 걸어주고 속성이 두개가 더 들어가있다.

  ​	shape라는 속성은 모형의 종류를 의미한다.

  ​	사각형이라면 rect, 원이라면 circle..등

  

  ​	coords라는 속성은 coords="25,25,75,75" 식으로 작성이 되는데 이 의미는

  ​	(25,25) 좌표부터 (75,75)좌표까지의 정사각형을 의미한다.

  

  ```
  	  <img alt="test" src="img/img00.jpg" width="100px" height="100px" usemap="#my"/>
  	  <map name="my">
  	  	<area alt="" shape="rect" coords="25,25,75,75" href="index.html" title="가즈아 인덱스"/>
  	  </map>
  ```

  

  ​	

  ​	