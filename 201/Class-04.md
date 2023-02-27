<h1>Functions JS</h1>

<h2>how functions work<h2>

```
function myFunc (param ) { // function paramter
//body console.log(param);
}
```

```
myFunc ("Hello") ; // parameter is hello // calls function
function sum(a + b //parameters inside here) {
let c = a  + b
return c;
console.log(c);
}
```

```
let myNewNumber = sum (10,5 // arguments inside here - outside function);
prompt ("Hey") ;
```

_anonymous function_
**An example of this using a circle **
radius of circle
a function is placed where an expression usually is

```
let circlePropls - function (radius) {
let area = Math.PI * radius * radius;
let circumference = 2* Math.Pi * radius;

return [area, circumference];
}

let circle3 = circleProps (3);

console.log(circle3)
}
```

<h2> Below are examples of how to use loops in JS</h2>

for loop coding challenge

```
for(let i = 0; i<=20; i = i + 2); {
  console.log(i);
}
// if i want to list all even numbers from 0-20
//because im adding 2 each time from 0
//shortcut i+=2 i=i+2);
```

If i want a list of all numbers from 1 to 10

```
for (let i=0; i<10; i++) {
console.log(i);
}

// it will run
0
1
2
3
4
5
6
7
8
9

if you move 0 to 1 and then make i less thanEQUAL to 10;
for (let i=1; i<=10; i++) {
console.log(i)
}

it will run
1
2
3
4
5
6
7
8
9
10

because 0 is the first number.
```

if putting

```
for (let i =0; false.....
```

It wont run - indetectable code

if

```
for (let i-0; true ....
```

we have an infinite loop

_Iterations_
const cleanTeeth =100;
for (let i =0; i < cleanTeeth; i ++) {
console.log('brush');
}
it will run the code 100 times and then stop.

to give an alert within the same example;

```
const cleanTeeth = 100;
for (let i=0; i <cleanTeeth; i ++) {
console.log('brush');
}
console.log('clean teeth');

```

Clean teeth will be on the 100th iteration.
