# table

> table이란 엑셀에서 표를 만드는 것과 같이 표를 만들어 주는 Tag이다.
>
> 기본 테이블 구조 만들기를 먼저 해보겠다.
>
> table Tag 안에는 tr Tag 와 th Tag를 사용한다.
>
> **tr Tag :** 한 행을 의미.
>
> **th Tag :** 내용을 의미.

```html
<table>
    <tr>
    	<th>제목1</th>
        <th>제목2</th>
    </tr>
    <tr>
    	<th>내용1</th>
        <th>내용2</th>
    </tr>
    <tr>
    	<th>내용3</th>
        <th>내용4</th>
    </tr>
</table>
```





- **table과 관련된 태그 사용**

  >table과 관련된 Tag [ thead, tbody, tfoot] 을 이용해 테이블을 만드는 것이다.
  >
  >thead : 테이블의 머리를 의미한다. 가장 맨 위를 뜻한다.
  >
  >tbody : 테이블의 몸통을 의미한다. 중간을 뜻한다.
  >
  >tfoot : 테이블의 발을 의미한다. 맨 아래를 뜻한다.
  >
  >caption : 테이블의 제목을 작성해주는 Tag
  >
  >colgroup : col의 group 을 의미. 그 안에는 col 이라는 Tag를 사용하는데 col = column 이라는 뜻이다. 칼럼이라는 의미로 행을 뜻한다.

  ```html
  <table>
      <caption>테이블의 제목</caption>
      <colgroup>
      	<col width="100px"/>
          <col width="200px"/>
          <col width="300px"/>
      </colgroup>
      
      <thead>
      	<tr>
          	<th>컬럼1</th>
              <th>컬럼2</th>
              <th>컬럼3</th>
          </tr>
      </thead>
      <tbody>
      	<tr>
          	<th>내용1</th>
              <th>내용2</th>
              <th>내용3</th>
          </tr>
      </tbody>
      <tfoot>
      	<tr>
          	<th>내용4</th>
              <th>내용5</th>
              <th>내용6</th>
          </tr>
      </tfoot>
  </table>
  ```

  

- **테이블 병합하기.**

  >테이블의 셀을 병합하는 것을 해보겠다.
  >
  >테이블 셀 병합의 속성에는 rowspan과 colspan이 있다.
  >
  >rowspan : 테이블의 [  세로열 합치기 ]
  >
  >colspan : 테이블의 [ 가로열 합치기 ]

  

```html
	<table>
		<caption>병합테이블</caption>
		<thead>
			<tr>
				<th>컬럼1</th>
				<th>컬럼2</th>
				<th>컬럼3</th>
				<th>컬럼4</th>
			</tr>
		</thead>
		
		<tbody>
			<tr>
				<td rowspan="2">1(세로-열-합치기)</td>
				<td>2</td>
				<td>3</td>
				<td>4</td>
			</tr>
			<tr>
				<td>6</td>
				<td colspan="2">7(가로-행-합치기)</td>
			</tr>
		</tbody>
		
		<tfoot>
			<tr>
				<td colspan="4">가로-행-합치기</td>
			</tr>
		</tfoot>
	</table>
```

