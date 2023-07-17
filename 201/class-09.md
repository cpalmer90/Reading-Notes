# events and forms

---

## creating a form.

Html:

<form id="addKittenForm"> 
<fieldset>
<legend>Basic info</legend>
<label for="nameInput"></label> 
<input type="text" id="nameInput" name="name">

<label for="interestInput"></label>
<input type="text" id="interestInput" name="interests">

</fieldset>
<fieldset>
<legend>
placement info
</legend>
<p>can be placed with</p>
<label class="inlineLabel">
<input type="checkbox" id="goodWithKids" Name="kids">
kids
<input type="checkbox" id="goodWithdog" Name="dog">
dog
<input type="checkbox" id="goodWithcats" Name="cats">
cats
</fieldset>
<button type="submit">Submit</button>
</form>
****

## CSS

_changing colour of button_
button(type="submit"){
background-color:red;
}

_making checklist inline_
.inline.input{
display:inline;
}

---

## JavaScript

---

`"use strict";
document.getElementById("click").addEventListener("click", function(){
    console.log("Hey what you think you are doing")
});
`

---

declare variable at top to keep things organised.
`const addKittenForm = document.getElementById("addKittenForm);`

`const allKittens = [];`
`this.pushKitty = function(){
    allKittens.push(this)
    console.log(allKittens)};`

`this.render();
this.pushKitty();`

`function renderAllKittens(){
for(let i = 0; i < allKittens.length; i++)
allKittens[i].render();}`

`addkittenForm.addEventListener("submit", function(event){ 
event.preventDefault();
console.log(event);
const name = event.target.name.value;
let interest = event.target.interest.value;
interest = interest.split(",");
const isGoodWithKids = event.target.isGoodWithKids.checked 
const isGoodWithDogs = event.target.isGoodWithDogs.checked 
const isGoodWithCats = event.target.isGoodWithCats.checked 
const imageUrl = "roger.jpg"
const newKitten = new Kitten(name, interests, isGoodwithkids, isgoodwithdogs, isgoodwithcats, imageUrl);
console.log(newKitten);
renderAllKittens();
addKittenForm.reset();
});`

`renderAllKittens();`

---

label tells user what input is for.
label selects input. good for screen readers. for input is linked to the input type.

---

## attributes:

- placeholder: attribute guides user to what they need to do.
- required: needs to be filled in to move forward
- max.length: limits characters with passwords

## inputs type:

- text:
- checkbox: for ticking\_
- radio:
- email:
- password:
- button:
- submit: makes button
- reset: reset button

---
