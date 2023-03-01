<h1>States</h1>

**_useState_** is a function that returns an array with 2 items a variable and a function that changes the value of that variable .

Destructerd useSTate, pageTitle , to the state and props.
set function that changes it-- (mutation function ) setPageTitle = useState ("string the title");
So we hve used useSTate

in header.js we pass the props in the curly brackets

**_useState_** specifically is making the state variable
**_props_** is how we pass things from parents to children

_bcs its a state variable , setting the variable with useState - we can set multiple variables with using mutation functions.?_

in app js.
make page title
parent - destructer - put brackets in fucntion and change it
also put it in the p tag to set the title

information can only go downwards
but we can use 'liftState' ... to go up.

eg. if you have props or an item that you want to send from child to parent . - have a click event in the child.js , effect the header.js

`liftState`

take the useState - clicksOnBuilding into app.js
then put props into parent, and pass it into child.

Is it worth putting everything in app.js?
NO - it would mean app.js is huge and then there are tiny components. Unless app.js needs access to all the comps.
if a state variable is only relevant to one comp - put it in there only.

<h2>Hosting a site</h2>

- setClicksOnBuilding - in app.js
- we pass to Parent
- Parent passes it to child
- we then run that function
  **That function doesn't run in child.js**
- _it runs in APP.js because it was declared there!_

- It 'bubbles up' to app.js then the information is passed to parent, header and then child.

all components have separate copies of information - which is just passing the 'prop' around. app.js declares it and then child calls it.

declaring functions in app.js
eg

````
<Header pageTitle={pageTitle} clicksOnBuilding={clicksOnBuilding} />```

in header.
````

export default function Child({ pageTitle , clicksOnBuilding}) {```

NB>
((you can delete node modules from past projects your not using
and then replace them back when you need them with npmi
to save on space. ))
