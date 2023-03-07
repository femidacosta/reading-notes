<h1>FILTERING with FORMS</h1>

<h2>Creating a form.</h2>

```import. "./app.js";

function App () {

  function handleSubmit

  //setting a function for submit button

  return (
    <div className="app">
    <h1> form </h1>
    <form>
    <input name ="colour" type="text" placeholder="this is a form">
    </form>
    <div>
  )
}
export default App;
```

````function handleSubmit (event) or (e)
event.preventDefault();```
//this function is going to run , and it is an event.
prevent default it - DONT REFRESH THE PAGE

STATE to handle the FORM <h2>

state- data the website is holding until you refresh

firstly.
```import {useState} from "react"```
// then using ```const``` add state variables inside [] .
[formDAta, setFormData]
use a mutation function (formData) to make any changes to value.
See below.

```<input name ="colour" type="text" placeholder="this is a form" value={formData}/>```

second

handleChange .. everytime we type in our input to make the value change use.
```onChange={handleChange}```

to be able to type and
````

event.target.value
target is just targetting the value we have added.
`<h2> {formData} </h2> `
is whatver we are typing into our form is goin to show below bcs we have set the value with `{formdata}`

if you want to add a label- you just set up another event function for label.

recap
**_handleChange_** is an eventListener function ( similar to OnClick) = as the value changes - do this.
we are calling it with **_onChange_**.
the **_target_** is the input itself.
everytime we run the onChange, it runs the target.
the **\*Value** is whats typed inside the form.

<h2>event.target.value = event is me changing it, target is the change, value is whats typed. </h2>

^^^ this is nothing to do with the **_submit function_**

handleSubmit

<h2>to add more inputs </h2>
add another input name="new input tag here"
we will need to change the formData because its now become and object. 
so change formData to formData.colour
and formData.newinputname, eg. dinosaur.

instead of doing
setFormData(event.target.value)

to put all the data from anothe object inside the new object {} using **_spread_**

let newFormData={} //object
setFormData (newFormData)

what is spread?

````const objOne = {
  name: "femi",
  age: 30,
}
const objTwo ={
  surname: "dacosta",
}
const obj Three ={ ...objOne, ...objTwo}```

***spread is ```...``` - take all the objects inside the objOne and objTwo***


if you put a new obj item inside the first objOne, it will create a new object with a new item.

```
_ _ _ _ _ _ _

when making a form - it can go inside any component.

if a component is doing 2 things, there should be 2 components.
rules applies to functions .

within form.js - new seperate component.

```export default function Form() {
  return (
    <form>
      <select>
        <option value="1">1</option>
        <option value="2">2</option>
        <option value="3">3</option>
      </select>
    </form>
  );
}
```

**NB.
good to get into the habit of thinking 'should this be a seperate component' so that your not writing code twice.
write it once, use a seperate component.**

````

to call upon this form.
we need to create a new function in app.js
const [hornsFilter, setHornsFilter] = useState("");
then we need to pass a new variable in main data. and because the for is in the header it must also go in header with a 'set' funtion.

```
 <div className="App">
      <Header hornsFilter={hornsFilter} setHornsFIlter={setHornsFilter}/>
      <Main data={data} handleModal={handleModal}hornsFilter={hornsFilter} />
```

set variable and mutation function
hornsFilter={hornsFilter}
setHornsFIlter={setHornsFilter}

now go to header and deconstruct into props.

to run a filter function
and return a conditional statement
to select number of horns.

`const filteredData = data.filter()`
