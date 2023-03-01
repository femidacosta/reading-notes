<h1> React and Component- Based Architecture </h1>

Class Outline

- overview of 301
- start learning how to create-react-app
- component based architecture
- intro to code challenges

What is React?
React.Js is a Js library. - it makes life easier

A component can be explained by looking at a header function; If you want to style a header on every page, you can write a block of code to do this rather than write that code for each page.

What is the difference between an arrow function and a function declaration?
You have to declare an arrow function .....

<h2>Turning a function declaration into an arrow function:</h2>
```
function doSomething(name) {
  // Do something
}

//this thing is a function - this is the name of the function
doSomething = (name) => {
// Do something
}

// Or make it a one liner!
doSomething = (name) => // Do something small
Difference between a constructor function and a class:

// constructor
function Cat(name) {
this.name = name;
this.fluffy = true;
}

Cat.prototype.speak = function () {
console.log(`${this.name} says meow`);
};

// to make a new instance
const bob = new Cat("Bob");
bob.speak();

to make this process easier we change the code from Prototype function to another function called Class.

```
<h2>Classes</h2>
```

// class
class Dog {
// this constructor runs only once
constructor(name) {
this.name = name;
this.fluffy = true;
}
//this run of code is just to run the new dog code
// when you call new dog - this function runs

// speak is a function - console.log dogs name speak
speak = function() {
console.log(`${this.name} says meow`)
}

// to make a new instance
const bob = new Dog("bob");
bob.speak();

```

Final example ;

```

Class Animal {
constructor (props) {
// props in an object
this.name = props.name;
this.color = props.colour;
}
}

const spot = new Animal ({name: "spot", color: "Black"})

- make notes on the above

---

to create a folder for create react app in ubuntu
**step 1**- npx create-react-app 'foldername' >(folder)

if it says high severity etc- dont worry about them its just letting you know that there are packages you havent used and its suggesting a delete.

**step 2** - ls in to folder, code .
**step 3** - within the README there are directions to tell you how to use.

_Packagelock.json_ - never edit.
_gitignore_ - it wont push to github
_node-modules_ not push to git hub - its too big
_public folder_
_src folder_
//We create the App within here.

`cntrl-shift-backtick `
//this opens a terminal inside VScode.

<h2> **to start running the project.**</h2>
```npm start```

**_ To start an app _**

Notes
{ `className` - we use this bcs we are writing in REACT - `class` is already something. }
-remember divs are block and buttons are inline block

- a compontent is something we can use multiple times
- we can put the rows and grid into a component
  `./` - where i am now
  `../` - go back a folder
  `props` - 'properties' is an object in React.
  `super` - is the parent function
  'npx' - node package execute

make div
make row
add buttons 1-3

Create React App
imports /exports are like a staging area

first - make new files for header, footer, main.
