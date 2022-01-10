1. What does thread of execution means in JavaScript?
- thread of execution means, when we run code a global execution context is created and this context loads all the code one by one is excuted in the global execution context depending upon whether it is a function or a normal line of code.

2. Where the JavaScript code gets executed?
- JS code gets executed in Global execution context in JS engine.

3. What does context means in Global Execution Context?
- Content means the area/terittory in which the code gets executed.

4. When do you create a global execution context.
- when we run our code JS engine first creates Global execution context and thereby it creates function execution context. 

5. Execution context consists of what all things?
- Execution context consist of execution area and memory. Execution area is the place in which  the code gets executed and the memory is created for any variables/function to store.

6. What are the different types of execution context?
- We have GEC and Function execution context. 

7. When global and function execution context gets created?
- The moment we run our code GEC gets created and if that code has any functions in that then the function exeuction context gets created. 

8. Function execution gets created during function execution or while declaring a function.
- FEC gets created when there is a function call. 

9. Create a execution context diagram of the following code on your notebook. Take a screenshot/photo and store it in the folder named `img`. Use `![](./img/image-name.png)` to display it here.



```js
var user = "Arya";

function sayHello(){
  return `Hello ${user}`;
}

var userMsg = sayHello(user);
```

<!-- Put your image here -->

![](./img/image-name.jpg)



```js
var marks = 400;
var total = 500;

function getPercentage(amount, totalAmount){
  return (amount * 100) / totalAmount;
}

var percentageMarks = getPercentage(marks, total);
var percentageProfit = getPercentage(400, 200);
```

<!-- Put your image here -->

![](./img/image-name.jpg)



```js
var age = 21;

function customeMessage(userAge){
  if(userAge > 18){
    return `You are an adult`;
  }else {
    return `You are a kid`;
  }
}

var whoAmI = customeMessage(age);
var whoAmIAgain = customeMessage(12);
```

<!-- Put your image here -->

![](./img/image-name.jpg)