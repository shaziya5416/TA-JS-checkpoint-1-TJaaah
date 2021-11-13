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
//first will return the value whereas second will just display the value and return undefined

2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.
first=a+b, second= undefined

3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?
it will add the first two number which is 12+24 that is 36

4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?
ye we can because it is returning

5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.
function sayHello(name){
return`name`;
}

6. What will be the output of the function below and why?

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage();
```
Hello,John

7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); // John

showMessage(); // Hello,JOhn

alert(userName); // John
```

8. What is a Anonymous Function give example of three functions.
Where we do not have the function name. 

9. Can function declaration be a Anonymous Function? Explain
Yes maybe because we may store the value of the function in another variable and declare it.

10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.

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
1.Should use camel casing
2.Should not be notrelateble to the work.
3. Should try to avoid numbers or special characters
4. Should be modular
5.The naming should be correctly done no matter how long 
