To create the execution context diagram consider the following:

- Global and Function Execution Context
- Different Phases Of Execution Context
  A) There are two phases of execution context one is Declaration or creation phase and Execution Phase context
- Var let and const

A) var is an global scope function and let & const is block scope function

Create the execution context diagram of the following code line by line.

```js
let num = 21;
function square(num) {
  return num * num;
}
let hundred = square(10);
console.log(hundred);
```

![][./images/img1.jpg]

Create the execution context diagram of the following code line by line.

```js
var num = 21;
function addFive(n) {
  return n + 5;
}
var five = addFive(0);
var ten = addFive(5);
console.log(five, ten);
```

![][./images/img2.jpg]

Create the execution context diagram of the following code line by line.

```js
let marks = [34, 45, 56, 76];
function multiplyArrayByN(arr, n) {
  let finalArr = [];
  for (let elm of arr) {
    finalArr.push(elm * 2);
  }
  return finalArr;
}

let numbers = multiplyArrayByN(marks);
```

![][./images/img3.jpg]

Create the execution context diagram of the following code line by line.

```js
counter();
function counter(){
  let count = 0;
  funciton increment(){
    return count++;
  }
  return increment()
}
```

![][./images/img4.jpg]

Create the execution context diagram of the following code line by line.

```js
counter();
let counter = function () {
  let count = 0;
  function increment() {
    return count++;
  }
  return increment();
};
// The counter is not a function thats why its through into an error
```
