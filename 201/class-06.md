'use stict'
console.log("Hello cool cat");

**start by declaring variable (const) then name variable. then set value = to an object use {}.**
create list of key value pairs.

each key value pair is seperated by a comma and ; to seperate value name and value.
const cat = {

name:"bob",
age:0
interests: ["cuddling", "eating", "sleeping"],
isGoodWithKids: true,
isGoodWithDogs: false,
isGoodWithOtherCats: true,

};

console.log(cat);

**_ to access properties in an object :
.notation : console.log(cat.name);
square bracket notation : console.log(cat["isGoodWithKids"]); _**

**update the key value pairs of the object**
cat.age = 3;
cat["name"] = "eric";
console.log(cat);

**function can be inside an object this is called a method**

const cat = {

name:"bob",
age:0
interests: ["cuddling", "eating", "sleeping"],
isGoodWithKids: true,
isGoodWithDogs: false,
isGoodWithOtherCats: true,
getAge: function(){
console.log(age);

<!-- this.age = randomAge(3,10) + "months"
}
getName: function(){
    console.log(age);
    this.name = randomName()
} -->

_number: function( ) {
console.log(7);
}_
};

cat.number();
cat.getAge();

**creating a random number** **Math.floor rounds number down to whole number.**
function randomAge(min,max){
return Math.floor(Math.random() \* (max - min + 1) + min)
}

**_this_**
This. key words use inside of object references the object it is manipulating.

---

**document object model - programme interface for web documents.**
gwt an element by its id and store it in a variable names parentElement
const parentElement = document.getElementById("kittenProfiles");
console.log(parentElement);

**creating elements**
const article = document.createElement("article")
parentElement.appendChild(article); -_append - write something to the end of a written document._

const h3 = document.createElement("h3");
h3.textContent = cat.name;
article.appendChild(h3);

const p = document.createElement("p");

<!-- p.textContent = cat.name + " is adorable and is " + cat.age + " old."; -->

p.textContent = `${cat.name}` is adorable, and is ${cat.age} old.
article.appendChild(p);

const ul = document.creatElement("ul");
article.appendChild(ul);

for(let i = 0; i < cat.interest.length; i++){
const li = document.createElement("li");
li.textContent = cat.interest[i]
ul.appendChild(li)
}

const img = document.createElement("img");
img.setAttribute("src", "images/" + cat.name + ".jpeg");
img.setAttribute("alt", cat.name + "looking good");
article.appendChild(img);

---
