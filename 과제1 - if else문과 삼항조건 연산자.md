주어진 if...else 문을 삼항 조건 연산자식으로 바꿔보세요.  

```js
// if...else문
var x = 11;
var res;
if (x === 0) {
  res = '영';
} else if (x % 2 === 0) {
  res = '짝수';
} else {
  res = '홀수';
}
```






삼항 조건 연산자  
```js
// 삼항 연산자
x= 11;

var result = x === 0 ? '숫자 영' :  x % 2 === 0 ? '짝수' : '홀수' ;
console.log(result);
```