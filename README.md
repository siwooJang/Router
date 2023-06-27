
---
---
---

Login Function make

![bandicam 2023-06-26 23-48-30-921](https://github.com/siwooJang/Router/assets/88125431/078ed630-2ef2-4e72-bc42-1e6d4039f673)

---
---
---

Home page make

![image](https://github.com/siwooJang/Router/assets/88125431/4809bcbe-1532-4372-affe-1ffced527e70)

---
---
---

First Router test

![Honeycam 2023-06-23 23-19-18](https://github.com/siwooJang/Router/assets/88125431/81e2b5ab-89ee-4aef-b915-09125b4f4853)

---
---
---

study :

리덕스 저장소 : Appstate type 저장 공간
Reducer : 현재 상태와 액션이라는 2가지 매개변수로 상태를 만들어서 반환

useSelector 훅으로 Appstate 속성값을 얻을 수 있음

useDispatch 리덕스 저장소에 저장된 속성값을 변경하려면 액션을 만들어야 하고, 

액션은 dispatch() 함수를 써서 리덕스 저장소에 전달해야함. 
전달할때 리듀서가 관여

dispatch() 액션 -> 리듀서 -> 리덕스 저장소 



이를 보여주는게 useReducer 함수 

리듀서를 합칠때 combineReducers() 를 사용 

payload : 이름없는 타입의 교집합 action.payload로 사용해야함 
사용하는 이유 pg 403 

리듀서는 순수함수여야 한다.
순수함수와 불순함수의 예시 보기  pg 405



리듀서가 반드시 순수함수 여야 한다는 것을 보완해주는것 = 리덕스 미들웨어

리덕스 미들웨어는 리듀서보다 먼저 실행해서 
부작용이 있는 코드들을 실행 결과를 리듀서 쪽으로 넘겨줌.

미들웨어의 출력내용을 확인해보는게 리덕스 로거

가장 많이 사용되는게 썽크 미들웨어  



칸반 보드 : 카드 목록을 수직방향으로 구성해서 
드래그 앤 드롭으로 순서 자유롭게 변경 가능 

객체의 속성값을 얻으려면 Record라는 타입을 이용해야함.
키 타입과 값 타입 2개의 타입 변수를 지정해야하고,
객체의 특정 속성에 접근할 수 있도록 하는 색인 연산자를 사용해 
속성값을 설정하거나 얻기 가능.

react-dnd , react-beautiful-dnd 에서  droppabble, draggable 제공

배열 변경 , 제거, 삽입하기 위해 유틸리티함수 구현하고,
Drag 관련 콜백 함수를 구현
