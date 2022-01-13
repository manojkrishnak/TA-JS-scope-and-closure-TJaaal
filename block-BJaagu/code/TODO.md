Find the output of the code snippets below:

```js
console.log(numA + numB); //OUTPUT
var numA = 21,
  numB = 30; // undefined + undefined = NaN
```

Find the output of the code snippets below:

```js
console.log(numA + numB); //OUTPUT
let numA = 21,
  numB = 30; //numA is not defined
```

Find the output of the code snippets below:

```js
let numA = 21,
  numB = 30;
console.log(numA + numB); //51
```

Find the output of the code snippets below:

```js
console.log(sayHello()); // OUTPUT
function sayHello() {
  console.log("Hey");
}
function sayHello() {
  console.log("Hello");
} //Hello
```

Find the output of the code snippets below:

```js
let username = "Tyrion";
sayHello(); // OUTPUT
function sayHello() {
  console.log(username);
}//Tyrion
```

Find the output of the code snippets below:

```js
sayHello(); // OUTPUT
let username = "Tyrion";
function sayHello() {
  console.log(username);// ReferenceError: username is not defined
}
```

Find the output of the code snippets below:

```js
let username = "Tyrion";
sayHello(); // OUTPUT
let sayHello = () => {
  console.log(username);
};//Uncaught ReferenceError: sayHello is not defined
```

Find the output of the code snippets below:

```js
sayHello(); // OUTPUT
let username = "Tyrion";
let sayHello = () => {
  console.log(username);
};//Uncaught ReferenceError: sayHello is not defined
```

Find the output of the code snippets below:

```js
sayHello(); // OUTPUT
var username = "Tyrion";
let sayHello = () => {
  console.log(username);
};//Uncaught ReferenceError: sayHello is not defined
```

Find the output of the code snippets below:

```js
var username = "Tyrion";
sayHello(); // OUTPUT
let sayHello = () => {
  console.log(username);
};//VM1859:2 Uncaught ReferenceError: sayHello is not defined
```

Find the output of the code snippets below:

```js
var username = "Tyrion";
let sayHello = () => {
  console.log(username);
  var username = "John";
};
sayHello(); // undefined
```

Find the output of the code snippets below:

```js
var username = "Tyrion";
let sayHello = () => {
  var username = "John";
  console.log(username);
};
sayHello(); // John
```

Find the output of the code snippets below:

```js
var username = "Tyrion";
let sayHello = () => {
  console.log(username);
  let username = "John";
};
sayHello(); // ReferenceError: Cannot access 'username' before initialization
```