States and Props \_ Learning REACT

REACT is a declarative, component based, Open source Library for building user interfaces.

**functional components produce cleaner code.**

<h2>Terminal Steps</h2>
New folder with create-react-app (then your file name) hit enter.

Firstly you need to prepare you files on VS Code
We have a list of files on the side, delete these files

keeping the files seperate files, it makes it easier to important certain components, as you might want to use the same components in different parts of the site.

---

In app.js
delete this code

```
  <header className="App-header">
        <img src={logo} className="App-logo" alt="logo" />
        <p>
          Edit <code>src/App.js</code> and save to reload.
        </p>
        <a
          className="App-link"
          href="https://reactjs.org"
          target="_blank"
          rel="noopener noreferrer"
        >
          Learn React
        </a>
      </header>
```

you should have this

````
import "./App.css";

function App() {
  return <div className="App"></div>;
}

export default App;```

Code along.
Making functional components

Create a folder called State and Props within React
in the components folder create Parent and Child folders

to create a parent component;
````

1 import React from "react";

export default function Parent() {
return(
<>

  <div></div>
  <h1>hello world</h1>
  </>
)
)

}

````

the way react does DOM manipulation - it needs to know
and bases a lot of what it does on each function
if you return 2 things it doesn't know which function is needs to return
there is always one parent and then you could do ```div``` inside a ```div``` but not outside.

fragments <> - <<< ***that*** is the syntax - is a way of using a syntax that isn't a div but it will be read as a div by the computer. Its a way of encapsulating the rest of the elements so that there is one parent element from the return.
 we don't need to use these too much, but if you were building a really extensive application , fragments are faster and more effecient.

for example ;
return (
  <>
  or use <header>
  or <section>

)
````

<br>
<br>
<p>
How to write JS inside of our function 
Write it before the returned JSX>>> 
***after function , before return***</p>

```function App() {
  // functional component

  const childName = "building";

  return (
    <div className="App">
      <h1>State and Props</h1>
      <h2>The building looks like origami {childName}</h2> // writing JS inside JSX
      <Parent />
    </div>
  );
}

export default App;
```

---

PROPS - A custom attribute we can set to any component.
like src or alt - we add it to a componnent and we can set that = to the component eg.
` Child name =childName`

example;

**in child.js**

```
export default function Child(props) {

<h2> The is and example of {props.name} {props.surname} </h2>

But this isnt nessacary so therefore we would use.

export default function Child(name, surname) {

The is and example of {name} {surname}
```

<br><br>

LAB

-change class components to functional components
