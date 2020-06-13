# HTML 기본구조

> - HTML이란?
>
>   Hyper Text Markup Language이라고 한다.
>
>   온라인상의 문서를 만들기 위한 구조화된 언어이다.
>
>   태그로 문서를 구조화 시켜주는거라고 볼 수 있다.



![](C:\Users\rgusq\AppData\Roaming\Typora\typora-user-images\image-20200614043051202.png)

>Client가 Server에게 요청[request]하면 HTTP[통신규약]에 의해 HTML 문서를 정해진 모양으로 응답[response]한다.
>
>*Client가 보는 화면은 Server가 보내준 모양대로 나타난다.



#### DTD(Document Type Definition) 선언

- Strict : 선언된 html 버전의 문법과 구조를 정확하게 사용.

  ```html
  <!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01 Strict//EN" "http://www.w3.org/TR/html4/strict.dtd">
  ```

  

- Transitional : 선언된 html 버전 이외의 문법과 구조를 활용.

  ```html
  <!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
  ```

  

- Frameset : Transitional + frame 지원( 사실상 Transitional과 동일 )

  ```
  <!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01 Frameset//EN“ "http://www.w3.org/TR/html4/frameset.dtd">
  ```



#### 문서를 정의(head)하는 기본 Tag

> meta : 문서의 기본 정보 등을 정의
>
> title : 문서의 제목 정의
>
> script : 자바스크립트 정의
>
> style : css를 정의
>
> link : 외부 문서를 연결할 때 정의