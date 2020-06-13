# form-01

- **form :** 

  >웹페이지에서의 입력 양식을 의미한다.
  >
  >ex ) 로그인창,회원가입창 등등
  >
  >form Tag를 사용하기 위해서는 name 속성, action 속성, method 속성을 사용한다.
  >
  >- name : name은 해당 form Tag를 쉽게 찾기 위해 이름을 붙여준다고 생각하면 된다.
  >
  >- action : form 데이터가 전송되는 url을 입력하는 곳이다.
  >
  >- method : form이 전송되는 방식이 있는데 [ get, post ] 가 있다.
  >
  >  get 방식은 header부분에 값을 담아서 전달하고
  >
  >  post는 값을 숨겨서 전달한다.

- **input :** 

  >input Tag는 사용자가 클릭할 수 있는데 버튼이 제공되며 type 이라는 속성과 name, value라는 속성을 줄 수 있다.
  >
  >- text  : 일반 문자들을 입력할수 있는 텍스트창이 만들어 진다.
  >
  >- password : text와 같지만 입력한 문자가 '*'로 숨겨져서 보여진다.
  >
  >- radio : 선택할 수 있는 체크박스가 나오고 중복 선택을 할 수 없는 박스가 제공된다.
  >
  >  ​			이 속성을 사용할 때에는 name을 같이 주게 되는데, name이 같을 경우에는 중복을 			할 수 없고 name이 다를 경우에는 중복체크를 할 수 있다.
  >
  >- checkbox : 중복 선택이 가능한 박스가 제공된다.
  >
  >- button : 일반적인 버튼만 제공되고 아무런 기능이 없다.
  >
  >- reset : 취소를 해주는 버튼이 제공된다. ( 초기화 )
  >
  >- submit : 작성한 것들을 제출해주는 버튼이 제공된다.
  >
  >- file : 파일을 업로드할 수 있는 버튼이 제공된다.
  >
  >- hidden :  사용자에게 보이지않는 숨은 요소이다.
  >
  >그리고 value 속성을 작성을 해야한다.
  >
  >value란 input 태그의 값을 명시한다.

```html
<form action="" method="post">
    <fieldset>
        <legend>회원가입</legend>
        아이디 : <input type="text" name="id"/>
        비밀번호 : <input type="password" name="pw"/>
        이메일 수신여부 <input type="radio" name="rd" value="Y"/>Y
        			  <input type="radio" name="rd" value="N"/>N
        
        관심분야
        <input type="checkbox" name="cb1" value="html">html
        <input type="checkbox" name="cb2" value="css">css
        <input type="checkbox" name="cb3" value="js">js
        <input type="checkbox" name="cb4" value="jq">jq
        
        <input type="button" value="그냥 버튼"/>
        <input type="reset" value="취소"/>
        <input type="submit" value="전송"/>
        
        <input type="file"/>
        <input type="hidden" name="hiddenval" value="my hidden value"/>
    </fieldset>
</form>
```

>위의 예제에서는 fieldset 태그와 legend 태그를 사용했다.
>
>- fieldset :  form양식에 관련된 태그들끼리 묶어주며 관계 태그 주위에 박스를 그립니다.
>
>  ​				fieldset 은 주로 legend와 같이 사용된다.
>
>- legend : fieldset 요소에 대한 설명글이라고도 하고 제목이라고도 할 수 있다.

![](https://postfiles.pstatic.net/MjAyMDA2MTRfNSAg/MDAxNTkyMDcwNzcxMzcw.OWTVFgUtbjVm69NrS-b2XGfp8PvXjFIRmxUYDwaUTt8g.linekwnbZghaTOwI83VthBeA1v1mcxglE-6p5k97Mr8g.PNG.rgusqls/image.png?type=w773)

