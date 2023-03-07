<h1> HTML forms and JS events </h1>

Javascript vent - when the user does something or when something happens in the DOM.

an html form is used to collect user input

event.preventDefault () - you need it or your forms WONT work.

<h2>Html Forms</h2>

```
<div class="form">

<form id="new-store-form"> // want to give it an id
		<fieldset>
				<legend>Enter New Cook ie Store:</legend>
				<label for="name-input">Store Name:</label>
				<input name="name" id="name-input" type="text" />
				<label for="min-cust-input">Min Customers / hour:</label>
				<input name="minCust" id="min-cust-input" type="text" />
				<label for="max-cust-input">Max Customers / hour:</label>
				<input name="maxCust" id="max-cust-input" type="text" />
				<label for="avg-cookies-input">Average Cookies sold / hour:</label>
				<input name="avgCookies" id="avg-cookies-input" type="text" />
				<button id="submit-button" type="submit">SUBMIT</button>
		</fieldset>
	</form>
</div>
```

in JS
`const btn = document.get ElementID("btn");`

//i want to listen for an event with this button
btn.addEventListener("click" , function () {
btn.
//this is going to run everytime someone clicks the button ^
})

function addSalmon ()

---

notes for making a form************\_\_************

Classlist is preexisting term

`<input>` is a self containting tag and its the main thing we need for a form

radio - you can only choose one option on the form

`<input name="name" id="name-input" type="text" />`
this is important because

html select is a drop down menu

placeholder in html creates a background text for where you type.

Make sure you put label names otherwise you wont know what it is.

to submit form
you can put ;

````<button id-"submit button" type> "submit" <button>
</form>```
this is important  bcs because it triggers the function?
````
