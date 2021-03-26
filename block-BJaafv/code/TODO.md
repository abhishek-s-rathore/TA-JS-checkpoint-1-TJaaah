1. What is the difference between the two `sum` function given below?

```js
// first
function sum(a, b) {
  return a + b;
}

// second
function sum(a, b) {
  console.log(a + b);
}
```

EXPLANATION : First function will return the sum of two numbers, we can use it by storing it in any variable while second function will print the value on console screen. It can lock value but will not store it.

2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.

EXPLANATION : first function will return a value which can be stored, while second function will console value, and return the undefined.

3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?

EXPLANATION : first two arguments will work and give some , third argument is of no use, since no third parameter is given.

4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?

EXPLANATION : Yes; we can store it, since function is an object i.e. value i.e. expression and expression can be written on the right side of assign operator.

5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.

SYNTAX :

```js
function sayHello(name) {
  return `Hello ${name}`;
}
```

6. What will be the output of the function below and why?

```js
let userName = "John";

function showMessage() {
  let message = "Hello, " + userName;
  return message;
}

showMessage();

// "Hello, John"
```

7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = "John";

function showMessage() {
  let message = "Hello, " + userName;
  return message;
}

alert(userName); // " John"

showMessage(); // ""Hello, John"

alert(userName); // "John"
```

8. What is a Anonymous Function give example of three functions.

SYNTAX :

```js
// These are the functions without name, for calling/ execution these are stored in any variable.

const addNumbers = function (a, b) {};
const getSquare = function (num1) {};
const checkPrime = function (num2) {};
```

9. Can function declaration be a Anonymous Function? Explain.

EXPLANATION : Since anonymous functions does not have name, so for calling we have to store them in any variable, so due to assign operator, it becoms an expression, hence it is not an declaration.

10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.

SYNTAX :

```js
const addNumbers = function (a, b) {};
const getSquare = function (num1) {};
const checkPrime = function (num2) {};
const evenOrOdd = function () {};
const printMessage = function () {};
```

```md
Functions are actions. So their name is usually a verb. It should be brief, as accurate as possible and describe what the function does, so that someone reading the code gets an indication of what the function does.

It is a widespread practice to start a function with a verbal prefix which vaguely describes the action. There must be an agreement within the team on the meaning of the prefixes.

For instance, functions that start with "show" usually show something.

Function starting with…

"get…" – return a value,
"calc…" – calculate something,
"create…" – create something,
"check…" – check something and return a boolean, etc.
```
