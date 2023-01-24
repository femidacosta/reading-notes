my code for lab 02 (JS)

```
"use strict";
let user = prompt("What is your name?");
alert("The user's name is " + user);
alert("Hi there, " + user);
let question = confirm("Are you feeling good today?");
alert(question);
if (question == true) {
  alert("Great News!");
} else {
  alert("Ah hopefully that changes throughout the day!");
}
let question2 = confirm("Do you think you could become a coding wizard?");
alert(question2);
if (question2 == true) {
  alert("lets do this!!!!");
} else {
  alert("Its not for everybody I guess!");
}
let colour = prompt("What is your favourite colour");
colour = colour.toUpperCase();
switch (colour) {
  case "blue":
    alert("your favourite colour was blue, hm!");
    break;
  case "orange":
    alert("Nice. Good choice, thats a motivating colour");
    break;
  default:
    alert("Can you choose between blue or orange?");
}
let genreOfMusic = prompt("What is your favourite genre of music?");
alert("Your favourite is" + genreOfMusic);
alert("Hi there, Your favourite genre of music is " + genreOfMusic);
switch (genreOfMusic) {
  case "pop":
    alert("Your favourite genre of music is pop, lets widen that search");
    break;
  case "reggae":
    alert("Lets share music!");
    break;
  case "electronic":
    alert("Lets share music!");
    break;
  case "punk":
    alert("Lets share music!");
    break;
  default:
    alert("Can you choose between any genre?");
}
```
