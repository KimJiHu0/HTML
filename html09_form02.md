# form02

>form Tag에는 전 글에 작성한 Tag들 뿐만 아니라 여러가지 요소를 쓸 수 있다.
>
>- select : 단어 뜻 그대로 사용자가 선택할 수 있는 목록창이 만들어진다.
>
>- textarea : 여러줄을 입력할 수 있는 텍스트 창이 제공된다.
>
>- optgroup : 옵션의 목록이 길 경우 관계가 있는 옵션들끼리 묶어주는 기능을 한다.
>
>- option : 옵션을 만들어주는 태그이다. option Tag는 value 속성과 같이 사용되는데 value는 서버             
>
>  ​               에 전달 될 값을 의미한다.

```html
<form action="" method="get">
    <fieldset width="300px" height="300px">
        <legend>여러줄 상자와 목록상자</legend>
        	<p>
                <label for="reply">답글</label>
                <!-- label은 이름을 붙여준다는 것과 같은 의미. -->
                <textarea rows="3" cols="30" id="reply" name="re"></textarea>
                <!-- 속성 rows와 cols가 주어지는데 row : 세로를 의미 cols : 가로를 의미-->
            </p>
    </fieldset>
</form>
```

>위의 예제는 textarea Tag를 사용한 예제이다.
>
>textarea 에는 속성을 줄 수 있는데 **rows** 는 세로의 길이를 의미하고, **cols**는 가로의 길이를 의미한다.

```html
       <p>
		과목선택
        <select name="sel01">
            <option value="html">html</option>
            <option value="css">css</option>
            <option value="js">js</option>
            <option value="jq">jq</option>
        </select>
       </p>
```

>위의 예제는 option을 사용한 예제이다.
>
>목록창이 제공되면서 사용자가 선택할 수 있게 된다.

```html
<select name="sel02">
    <optgroup label="분식">
        <option value="ddukbokki">떡볶이</option>
        <option value="sundai">튀김</option>
        <option value="mandu">만두</option>
        <option value="tuikim">튀김</option>
        <option value="jjolmen">쫄면</option>
    </optgroup>
    <optgroup label="과자">
    	<option value="pokachip">포카칩</option>
        <option value="butterring">버터링</option>
        <option value="mom's pie">엄마손파이</option>
        <option value="chaldduckpie">찰떡파이</option>
        <option value="kkobukchip">꼬북칩</option>
        <option value="homerun ball">홈런볼</option>
    </optgroup>
</select>
```

>위의 예제는 optgroup를 사용한 예제이다.
>
>optgroup는 label에 분식을 씀으로써 사용자에게 보여지는 화면에는 '분식' 이라는 옵션창이 제공되
>
>지만 사용자가 선택할 수 없다. 관계가 있는 option끼리 묶어주는 역할을 한다.

![](https://postfiles.pstatic.net/MjAyMDA2MTRfMTM3/MDAxNTkyMDcyNzU3Mjc2.Jp8hme3LGGnE8IwrrEgREI_Oy3Z25--Q001QPGaBQN8g.O2HlU48JvREdD4ksUhIXN-MxMOPRG5ga01CSvt950pcg.PNG.rgusqls/image.png?type=w773)

>위의 세가지 Tag들을 사용한 결과창이다.
>
>보고 익혀두도록 하자