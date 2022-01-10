1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here
let percentage = function (marks, total) {
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
let percentage = function (marks, total) {
  return (marks * 100) / total;
}

```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};

function percentage(marks, total) {
  return (marks * 100) / total;
}
```

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};

function percentage(marks, total) {
  return (marks * 100) / total;
}
```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};

function percentage(marks, total) {
  return (marks * 100) / total;
}
```

```js
let percentage = (marks, total) => (marks * 100) / total;

function percentage(marks, total) {
  return (marks * 100) / total;
}
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.
- In JS all functions are objects. Since all functions are objects we can store this function to a variable and we can call with this variable name to execute the function. 
```js
let percentage = (marks, total) => (marks * 100) / total;

function percentage(marks, total) {
  return (marks * 100) / total;
}
```

4. Why is a function call an expression in JavaScript?

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // 5
five = add; // function add(a, b) {return a + b}
five = five(10, 11); // 21
five = function () {
  return 'Hello';
}; // hello
```

6. What is the difference between function definition and function call? Explain with an example.
- function definition is the definition of the function which includes set of instructions to accomplish a specific task whereas function call is to excute the function with the function name to run this set of instructions

7. What is the similarities between function definition and function call?
- The onky similarity between function definition and call is the name the of the function is being used to call/execute the function.

8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid 
```

9. What is higher order function explain with an example.
- A function which can take another function as an argument is called HOF. In the HOF we have 2 function: 1. base function and 2. supplier function. 
base function takes in the supplier function does some job and returns the output.
```js
let arr = arr.map(()=> arr.text);
```

10. Explain what is callback function. Why you can pass a function inside a function?
- The supplier function which we pass to base function is called callback function. We can pass a function inside a function because of HOF. This is the core functionality. 