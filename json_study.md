## JSON 
- JSON(JavaScript Object Notation)의 약자로 JavaScript에서 객체를 만들 때 사용하는 표현식을 의미한다.  
  이 표현식은 사람도 이해하기 쉽고 기계도 이해하기 쉬우면서 데이터의 용량이 작다.   
  이런 이유로 최근에는 JSON이 XML을 대체해서 설정의 저장이나 데이터를 전송등에 많이 사용된다.  

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


<br/>

## 참고 사이트 
- https://json.org/json-ko.html
