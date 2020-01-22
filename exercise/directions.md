

# Exercises: JavaScript loops

Paste your answers into this file.

<br>

## Print every number from 0 to 10

```
ANSWER HERE
```

<br>

## Print every number from 10 to 0

```
for(i=10;i>=0;i--){
console.log(i);
};
```

<br>

## Print every number from 4 to -16

```
for(i=4;i>=-16;i--){
console.log(i);
};
```

<br>

## Print every fifth number from 8 to 41

```
for(i=8;i<=41;i+=5){
console.log(i);
};
```

<br>

# Exercises: JavaScript loops with array:

Paste your answers into this file.



1. Change all **odd** numbers to be those numbers multiplied by two:
```js
const numbers = [4, 9, 7, 2, 1, 8];

  // your code here
const changeOdd =function(num) { 
  return  num=num*2;
}
const numbers = [4, 9, 7, 2, 1, 8];
for(let i=0;i<numbers.length;i++){
    if(numbers[i]%2!==0)
  numbers[i]=changeOdd(numbers[i]);
}
numbers; // => [4, 18, 14, 2, 2, 8]
```

2.  Create an array to hold your favorite colors.  For each choice, log to the screen a string like: `My #1 choice is blue.`

```js
// my code will git the first five colors and print it in the console 
// and save it into favoriteColors Array 
const favoriteColors =[];
for(let i=1;i<=5;i++){
var person = prompt("My #"+i+" choice is :", "");
favoriteColors[i-1]=person;
if (person != null) {
    console.log( "My #"+i+" choice is :"+person);
    person=null;
}
}
```
3.  Create an array of ages.  Loop through and log only the ages that are over 21.

1. Create an array to hold your top five choices of something (music, books, movies, whatever).

    - For each choice, log to the screen a string like: "My #1 choice is blue."
    - **Bonus:** Change it to log "My 1st choice, "My 2nd choice", "My 3rd choice", picking the right suffix for the number based on what it is.


## The classic Fizzbuzz Program

For every `number` between 1 and 100...

If the `number` is evenly divisible by 3, print "Fizz"

If the `number` is evenly divisible by 5, print "Buzz"

If the `number` is evenly divisible by 3 AND evenly divisible by 5, print "Fizzbuzz"


```
ANSWER HERE
```

<br>


## The even/odd reporter

Write a for loop that will iterate from 0 to 20. For each iteration, it will check if the current number is even or odd, and report that to the screen (e.g. "2 is even").

```
ANSWER HERE
```

<br>

## Multiplication Tables

Write a for loop that will iterate from 0 to 10. For each iteration of the for loop, it will multiply the number by 9 and log the result (e.g. "2 * 9 = 18").

Bonus: Use a nested for loop to show the tables for every multiplier from 1 to 10 (100 results total).


```
ANSWER HERE
```

<br>

## The Grade Assigner

Check the results for every value from 60 to 100 - so your log should show "For 89, you got a B. For 90, you got an A.", etc.

```
ANSWER HERE
```
