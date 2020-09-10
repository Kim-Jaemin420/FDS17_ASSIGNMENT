<!-- 1. 변수 x가 10보다 크고 20보다 작을 때 변수 x를 출력하는 조건식을 완성하라 -->
```js
x = 15;
if ( 10 < x && x < 20) {
  console.log(x);
}
```
<!-- 2. for문을 사용하여 0부터 10미만의 정수 중에서 짝수만을 작은 수부터 출력하시오. -->
```js
for (let i = 0; i < 10; i++) {
  if ( i % 2 === 0) console.log(i);
}
```
<!-- 3. for문을 사용하여 0부터 10미만의 정수 중에서 짝수만을 작은 수부터 문자열로 출력하시오. -->
```js
evenNum = '';
for ( let i = 0; i < 10; i++) {
  if ( i % 2 === 0) {
    evenNum += i;
  }
}
console.log(evenNum);
```
<!-- 4. for문을 사용하여 0부터 10미만의 정수 중에서 홀수만을 큰수부터 출력하시오. -->
```js
for ( let i = 10; i > 0; i--) {
  if ( i % 2 ) console.log(i);
}
```
<!-- 5. while문을 사용하여 0 부터 10 미만의 정수 중에서 짝수만을 작은 수부터 출력하시오. -->
```js
var even = 0;
while (even < 10) {
  console.log(even);
  even += 2;
}
```
<!-- 6. while문을 사용하여 0 부터 10 미만의 정수 중에서 홀수만을 큰수부터 출력하시오. -->
```js
var odd = 9;
while ( odd > 0) {
  console.log(odd);
  odd -= 2;
}
```
<!-- 7. for 문을 사용하여 0부터 10미만의 정수의 합을 출력하시오. -->
```js
var num = 0;
for ( let i = 0; i < 10; i++) {
  num = num + i;
}
console.log(num);
```
<!-- 8. 1부터 20 미만의 정수 중에서 2 또는 3의 배수가 아닌 수의 총합을 구하시오. -->
```js
var num = 0;
for ( let i = 0; i < 20; i++) {
  if (i % 2 !== 0 && i % 3 !== 0) {
    num = num + i;
  }
}
console.log(num);
```
<!-- 9. 1부터 20 미만의 정수 중에서 2 또는 3의 배수인 수의 총합을 구하시오. -->
```js
var num = 0;
for ( let i = 0; i < 20; i++) {
  if (i % 2 === 0 || i % 3 === 0) {
    num = num + i;
  }
}
console.log(num);
```
<!-- 10. 두 개의 주사위를 던졌을 때, 눈의 합이 6이 되는 모든 경우의 수를 출력하시오. -->
```js
for ( let i = 0; i <= 6; i++) {
  for ( let j = 0; j <= 6; j++) {
    if ( i + j === 6) {
      console.log(`[${i}, ${j}]`);
    }
  }
}
```
<!-- 11. 삼각형 출력하기 - pattern 1 -->
```js
for ( let i = 0; i < 5; i++) {
  triangle = '';
  for ( let j = 1; j <= i+1; j++) {
    triangle += '*';
  }
  console.log(triangle);
}
```
<!-- 12. 삼각형 출력하기 - pattern 2 -->
```js
for ( let i = 0; i < 5; i++) {
  triangle = '';
  for ( let j = 0; j < i; j++) {
    triangle += ' ';
  }
  for ( let k = 5; k > i; k--) {
    triangle += '*';
  }
  console.log(triangle);
}
```
<!-- 13. 삼각형 출력하기 - pattern 3 -->
```js
  for ( let i = 0; i < 5; i++) {
    triangle = '';
    for ( let j = 1; j <= 5-i; j++) {
      triangle += '*';
    }
    console.log(triangle);
  }
```
<!-- 14. 삼각형 출력하기 - pattern 4 -->
```js
  for ( let i = 0; i < 5; i++) {
    triangle = '';
    for ( let j = 1; j <= 5-i; j++) {
      triangle += ' ';
    }
    for( let k = 0; k <= i; k++) {
      triangle += '*';
    }
    console.log(triangle);
  }
```  
<!-- 15. 정삼각형 출력하기 -->
```js
  for (let i = 0; i < 5; i++) {
    triangle = '';
    for ( let j = 1; j < 5-i; j++) {
      triangle += ' ';
    }
    for (let k = 0; k < 2*i+1; k++) {
      triangle += '*';
    }
    console.log(triangle);
  }
```
<!-- 16. 역정삼각형 출력하기 -->
```js
  for (let i = 0; i < 5; i++) {
    triangle = '';
    for ( let j = 0; j < i; j++) {
      triangle += ' ';
    }
    for (let k = 9; k >= 2*i+1; k--) {
      triangle += '*';
    }
    console.log(triangle);
  }
```
  