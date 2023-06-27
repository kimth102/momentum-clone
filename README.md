javascript for beginners

basic data types
- number
    - integer : 1, 2
    - float : 1.4, 3.6
- string : "hello", 'hi'
- bool : true, false
- null : 아무것도 없는 상태. 자연적으로 생기지 않음.
- undefined : 존재하지 않는, 아무것도 아닌, 어떤 데이터 타입도 아닌 상태
    예. 선언 후 초기화를 하지 않은 경우

variables
- const : 변경 불가능. 상수.
- let : 변경 가능
- var : 변경 가능. 재선언 가능. 과거에는 var 만 있었음. 변수 통제가 어려우므로 사용x

- 일반적으로 const를 사용하고 변경이 필요한 경우에만 let을 사용

arrays
- 데이터의 리스트
- 선언 : const daysOfWeek = ["mon", "tue", "wed", "thu", "fri", "sat", "sun"];
- 데이터 접근 : daysOfWeek[0]
- 데이터 추가 : daysOfWeek.push("hi");

objects
- 선언 : const player = {
            name: "lynn",
            points: 100,
            sayHello: function () {
                console.log("hello my name is", this.name);
            },
        };
- 프로퍼티 접근 : player.name, player['name']
- 프로퍼티 갱신 : player.name = 'name2'
- 프로퍼티 추가 : player.level = 10

- object는 const로 선언해도 내부 프로퍼티는 갱신 가능, object 자체를 변경하는 것은 불가능

functions
- 반복 사용 가능한 코드 조각
- return: function 실행 완료 후 결과 전달
- 선언 : function plus(a, b) {
            return a + b;
        }
- 호출 : plus(1, 4)

conditionals
- if () {}
  else if () {}
  else {}

---

searching for elements
- getElementById()
- getElementsByClassName()
- getElementsByTagName()
- querySelector()
- querySelectorAll()

events
- addEventListener(event, function)
    - title.addEventListener("click", handleTitleClicked)
- element.onclick = event
    - title.onclick = handleTitleClicked