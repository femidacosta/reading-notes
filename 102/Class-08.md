Page not finished - notes taken and not formatted into a readable page


Computer Logic

Computer Loops
while the answer is incorect keep asking
Let myNum = 0; ( myNum is equal to 0) DECLARING NUMBER 

(((((( A while Loop
Test expression - true - body of while 
If false - exit loop ))))))

let number = 0;

//puts number in console log
while (number <10) {
  console.log(number)

  //increases number by 1 each loop
  number = number +1
}

simple but effective example.
 while hair is dirty - apply soap to hair , rinse it off
while hair is dirty keep washing. if hair not dirty stop washing.


increment (i)

i=i +1 
i-- ( will remove the loop) 

// initialisation; condition; increment
for(let a = 0; a < 10; a++){
  console.log(a * 10 )
}

--------------------------------------------------------------------------------
or 
let a = 3;
10 * a // 30

10 is still 10 
and a is 3 

the output of 10 x 3 (a) is 30 
a = 10 * a ( that means a would be 30) 

```
  alert ("No, try again")
```
- pop up , just an ok button 

```
// fuction to make the user guess a number
function guessANumber(){
    let answer;
    //while the answer is incorrect keep asking
    while (answer != 3) {
answer = prompt ("Guess a number between between 0 - 10");
// all we are doing is asking and doing nothing with response
// add the word 'answer', answer is equal to nothing so it will run the loop
if (answer != 3) {
    alert ("No, try again");
}else {
    alert("Nice, thats my lucky number");
}
    }
//invoke the question
guessANumber();
```
example 1 .


BOOLEAN

What is the difference between =,==, and === in JS?

The = (assigment operator) , == and === (relational operator) please explain the diffenerce between these 3 operators in javascript;along with relevant examples.And what do we mean by type type conversion in===,please explain with example.And why does

```
 3==='3'//false
    3==="3"//false
    "3"==3//true
    3===3//true
```
also why does

```
3==3//true
    "3"==3//true
    3=='3'//true
    1==true//true
```
By using = you assign a value to something.

```
x = 1 //x now equals 1
x = 2 //x now equals 2
```
By using == you check if something is equal to something else. This is not strict

```
x == 1 //is x equal to 1? (False)
x == 2 //is x equal to 2? (True)
true == 1 //does the boolean value of true equal 1? (True)
```
By using === you check if something is equal to something else. This is also strict.

```
x === 1 //is x equal to 1? (False)
x === 2 //is x equal to 2? (True)
true === 1 //does the boolean value of true equal 1? (False)
```
What strict does, in case it wasn’t clear there, is that it checks not only the equality of the two values, it compares the types of the two values too. Using == will try and convert one side of the expression to be the same type as the other. For example, boolean and integer. The boolean value for true is 1, therefore does 1 equal 1? Yes, true. When using strict however, it does not try and convert before doing the comparison, it checks if true equals 1, which is doesn’t as they are two different data types, and returns false.