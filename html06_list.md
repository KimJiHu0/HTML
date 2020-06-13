# list

> list에는 ' 순차적 목록 ', ' 비 순차적 목록 ', ' 정의형 목록 ' 이  있다.

- **순차적목록 :**

  >말 그대로 순차적으로 목록을 나열해주는 것을 의미한다.
  >
  >순차적 목록에는 'ol' Tag 안에 'li' Tag를 사용한다.
  >
  >순차적 목록이기 때문에 목록 앞에 번호가 새겨진다.
  >
  >'li' 안에 'ol'을 작성할 수 있다.

  ```html
  <ol>
  	<li>눈을 뜬다</li>
  	<li>밥 먹는다</li>
  	<li>지하철 탄다</li>
  	<li>내려서 걷는다</li>
  	<li>학원 올라오는 방법
  		<ol>
  			<li>엘베탄다</li>
  			<li>걸어올라간다</li>
  		</ol>
  	</li>
  </ol>
  ```

  ![](https://postfiles.pstatic.net/MjAyMDA2MTNfMjAy/MDAxNTkyMDUyMDAyNDg0.8Sf42pWTTcSp8zpHulWGlvizW7fhzUMhtGWZ8IvVC9wg.ThpDsbM73aBBPw0nRkozzvninDOOTJuEJK92pRsfo0sg.PNG.rgusqls/image.png?type=w773)

  

- **비 순차적목록 :**

  >비 순차적 목록은 위의 예제와 달리 순번이 없는 것을 의미한다.
  >
  >비 순차적 목록은 'ul' 안에 'li'를 사용한다.
  >
  >'li' 안에 'ul'을 사용할 수 있다.

  ```html
  <ul>
  	<li>강의실 나간다</li>
  	<li>카드를 찍는다</li>
  	<li>내려간다</li>
  		<ul>
  			<li>엘베탄다</li>
  			<li>걸어간다</li>
  		</ul>
  	<li>역삼으로 간다</li>
  	<li>지하철타고 건대역</li>
  	<li>환승해서 상봉</li>
  	<li>내려서 버스탄다</li>
  	<li>내려서 걸어서 집에 들어간다</li>
  </ul>
  ```

  ![](https://postfiles.pstatic.net/MjAyMDA2MTNfNTEg/MDAxNTkyMDUyMTk4NTAw.czwQ1A2tSxWGQQOhVJSmrnmAZIix9j9vA69oFU1yMGwg.v_UCSVEQP5F0k_mr4YSs0k3gXIYGY0dMwIBKux02AKwg.PNG.rgusqls/image.png?type=w773)

- **정의형 목록 :**

  >정의형 목록은 위의 예제들과 같이 똑같은 구조이다.
  >
  >하지만 특수문자나 순번이 없고 그냥 정의만 되어있어서 정의형 목록이다.
  >
  >정의형 목록은 'dl' 안에 'dt'을 작성하는데 이는 제목을 의미한다.
  >
  >그리고 'dl' 안에 'dd'를 사용해준다.

  ```html
  	<dl>
  		<dt>학원강의시간 [ 제목 ]</dt>
  			<dd>오전시간</dd>
  			<dd>점심시간</dd>
  			<dd>오후시간</dd>
  				<dd>
  					<dl>
  						<dt>좋아하는 파트</dt>
  						<dd>if</dd>
  						<dd>exception</dd>
  						<dd>ui</dd>
  					</dl>
  				</dd>
  	</dl>
  ```

  ![](https://postfiles.pstatic.net/MjAyMDA2MTNfNTQg/MDAxNTkyMDUyMzgwODk3.4foSNIbiUGbtnRAD4VCY9GfWCGi3ciGtIV-JpKT19zgg.RllVQNs1UNjbbG03M-wYhkjgqAFQvjbfr8HX9Me9F2Ig.PNG.rgusqls/image.png?type=w773)