## JSON 이란?
- JSON(JavaScript Object Notation)의 약자로 JavaScript에서 객체를 만들 때 사용하는 표현식을 의미한다.  
  경량의 DATA-교환 형식이며, 이 표현식은 사람도 이해하기 쉽고 기계도 이해하기 쉬우면서 생성함에도 용이하다.   
  이런 이유로 최근에는 JSON이 XML을 대체해서 설정의 저장이나 데이터를 전송등에 많이 사용된다.  
  JSON은 완벽하게 언어로 부터 독립적이지만 C-family 언어 (C, C++, C#, Java, JavaScript, Perl, Pythone) 그외 다수의 프로그래머들에게 친숙한 관습을 
  사용하는 텍스트 형식이다. 

<br/>

## JSON 요점
- simplest data interchange format
  - 데이터를 주고받을때쓸 수 있는 가장 간단한 데이터 포맷이다.
+ lightweight text-based structure
  - 텍스트를 기반으로한 가벼운 구조이다.
- easy to read
  - 읽기 편하다
+ key-value pairs
  - 키-밸류로 이루어져있는 파일 포맷이다. 
- used for serialization and transmission of data between the network the network connection
  - 데이터를 서버와 주고 받을때 시리얼라이제이션(직렬화)을 위해 사용하고, 데이터를 주고 받기 위해서 사용한다.
+ **dependent programming language and platform**
  - **그램 랭귀지나 플랫폼에 상관없이 사용가능하다.**


<br/>

## java의 객체 생성 예제
- 객체를 만들때 
```java
var person = {"height":174, "job":"programmer"}    객체를 만들때 중괄호 안에 height 와 job 이라는것은 쉼표(,) 로 구분된 규칙(약속)을 지켜야 한다.
var members = ["egoing", "k8805", "sorialgi"];     대괄호 안에 쉼표(,)로 구분하면 배열 규칙이라고 정한다. 
```
- 이런것들의 약속이 어려우니 JSON 으로 하게 됐다. 

<br/>

## JSON 형식 
```json
{
    "font_face": "Inconsolata",
    "font_size": 30,
    "ignored_packages":
    [
    ],
    "line_numbers":false
}
```

![image](https://user-images.githubusercontent.com/40311906/136728376-6f405587-c437-433f-a059-83977f763d21.png)


## JSON validator
- https://jsonformatter.curiousconcept.com/#
- https://jsonlint.com/
- https://jsonformatter.org/#

<br/>

## 참고 사이트 
- https://json.org/json-ko.html
