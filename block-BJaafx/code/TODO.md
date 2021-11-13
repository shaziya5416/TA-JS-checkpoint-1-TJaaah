1. Using loops take 10 inputs from user and find the average of all the numbers.
let sum=0;
var input;
var avg;
for(i=1;i<=10;i=i+1)
{
input=Number(prompt(`enter number`));
sum=input+sum;
}
avg = sum/10;
console.log(avg)
2. What will be the output of the code below

```js
let i = 0;
while (i < 3) {
  println('hi');
  i++;
}
```
///their is no println in js

3. Write a function named `getEvenSum` that accepts a parameter `max`. Return the sum of all even numbers. The value of max should default to 10.
var sum=0;
var max=10;
function getEvenSum(max){
for(i=0;i<=max;i=i+1){
if (i%2==0){
sum=sum+i;
}
}
return sum;
}

4. Write a function named `getOddSum` that accepts a parameter `max`. Return the sum of all odd numbers. The value of max should default to 10.
var sum=0;
function getOddSum(max){
for(i=0;i<=max;i=i+1){
if (i%2!=0){
sum=sum+i;
}
}
return sum;
}
5. Write a function named `getProductOfDigits` that accepts a parameter `num`. It returns the product of all the digits in the number.

- If the input value is less than 0 return `not a valid input`
- For example if the input is `123` output should be `6`.

6. What will be the output of the following code below in multiple conditions? Explain with reason?

```js
function check(num) {
  if (num > 5) {
    return 'Bigger than 5';
  }

  if (num < 5) {
    return 'Smaller than 5';
  }

  return num;
}

check(10); // Bigger
check(1); // Smaller
check(5); // 5
```

7. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') return 'You are arya';
  if (name === 'John') return 'You are john';
  return 'Who are you';
}

getOutput('Arya'); // `You are atya`
getOutput('John'); // `You are john`
getOutput(); // `who are you`
```

8. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') console.log('You are arya');
  if (name === 'John') console.log('You are john');
  return 'Who are you';
}

getOutput('Arya'); // what will be the output
getOutput('John'); // what will be the output
getOutput(); // what will be the output
```

9. Can a function have multiple return statement? Give one example if possible and explain the reason.
//Yes.ABove were the examplses

10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.
//in for the conditions of start and end are given ie the number of iterations are already known ; whereas in while we only have one value and a condition till which iterations are to be done
