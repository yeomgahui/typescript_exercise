#01

요구 사항 
- 주어진 데이터의 Interface를 정의하고, 이를 적절히 사용하세요.

> Interface란, 객체를 정의하기 위해 사용한다.

users 배열내에 정의 되어있는 객체의 속성은 다음과 같다.   
name, age, occupation    
그리고, 해당 속성은 각각 string, number, string을 그 타입으로 갖는다.    
위 정보에 의해 정의될 interface는 다음과 같다.   

```ts
interface User {
    name: string;
    age: number;
    occupation: string;
}
```

