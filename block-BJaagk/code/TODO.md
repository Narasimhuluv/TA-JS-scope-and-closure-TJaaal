1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here
let percentage = function(marks, total){
  return (marks * 100) / total;
}

let percentage = (marks, total) => {
  return (marks * 100) / total;
}
```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer
function Declaration
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;

  function expression
};
```

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};

function expression
```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};

function expression   // For making the function short using arrow keywords instead of function keyword
```

```js
let percentage = (marks, total) => (marks * 100) / total;

function expression 
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.

A) In Javascript Function is an Object. Function definition start with variable name in javascript , and also function stored in a variable.

4. Why is a function call an expression in JavaScript?

A) A function call expression is used to execute a specified function with the provided arguments.

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // Answer :- 5
five = add; // Answer it will take the refernce of above add function
five = five(10, 11); // Answer :- 21
five = function () {
  return 'Hello';
}; // Answer it will take as a reference of function five
```

6. What is the difference between function definition and function call? Explain with an example.
A) Function definition is declare the function. function call is excuting the function.

7. What is the similarities between function definition and function call?
A) There is no similarities between the function dfinition and function call because the function definition is an procedure of achieve the output. the function call is achieve the particular task

8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid or invalid - It is valid code the output is Sam
```

9. What is higher order function explain with an example.


A) higher order function accepts other function as an input parameters and it returns a function as an output
```js
let isOdd = function(num){
  return num % 2 === 0
}

function filterOdd(arr,fun){
  console.log(fun(23))
  return arr
}
filterOdd([1,2,3,4,5,6], isOdd)


// output :- False and "[1,2,3,4,5,6]"


```

10. Explain what is callback function. Why you can pass a function inside a function?

A)  callback function is a function that is passed as an argument to another function, to be “called back” at a later time. A function that accepts other functions as arguments is called a higher-order function,
