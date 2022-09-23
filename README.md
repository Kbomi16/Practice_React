# Practice_React

### #React.js
- 컴포넌트 기반 UI 라이브러리. 
- 특정기능은 커뮤니티 패키지를 통해 추가된다.

### #Angular.js
- 컴포넌트 기반 UI 라이브러리.
- 리액트보다 더 많은 내장 기능을 가지고 있음. 
- 타입스크립트 수용 

### #Vue.js
- 앵귤러와 리액트를 합쳐 놓은 것
- 컴포넌트 기반 UI 라이브러리. 
- 기능이 앵귤러보다는 적고 리액트보다는 많다.
- 라우팅 같은 핵심 기능을 포함하고 있어 커뮤니티 의존성이 낮음.

### #let & const
let : 값을 수정할 수 있는 변수를 선언할때
const : 한번 지정하면 절대 변하지 않는 값인 상수를 선언할 때

### #화살표 함수
```js
fuction myFun( ) {

}

const myFuc = ( ) => {

}
```

### #스프레드 연산자
모든 원소와 프로퍼티를 가져와서 새 배열이나 객체에 전달함.
... : 요소를 받아옴

```es6
const numbers = [1,2,3];
const newNumbers = [...numbers, 4];
console.log(newNumbers);   // [1,2,3,4]
```

### #레스트 연산자
```es6
const filter = (...args)=> {
  return args.filter(el => el === 1);
}

console.log(filter(1,2,3));   // 1
```

### #Destructuring
원소나 프로퍼티를 하나만 가져와서 변수에 저장함.

``` es6
const numbers = [1,2,3];
[num1, , num3] = numbers;
console.log(num1, num3);   //1  3
```


const number =1;
const num2 = number;
console.log(num2);   // 1

const person = {
  name: 'max'
};
const secondPerson = person;
person.name = 'Manu';

console.log(secondPerson);
// [object Object] {
//  name: "Manu"
//}

const person = {
  name: 'max'
};
const secondPerson = {
  ...person
};
person.name = 'Manu';

console.log(secondPerson);
// [object Object] {
//   name: "max"
// }






