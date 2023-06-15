# **Box Model** 
****

<form>
<label></label>
<input></input>
<button></button>
</form>

block level element - nothing can go beside it.

display: block;

#px-div { w100
h100
bc}

#pct-div {
    width: 90%
    height: 90%
    bc:
}

try not to use absolute height. instead try to use max and min height. 
#overflow-box{

    max-height:100px
    overflow: scroll;
}

#bmp-box { 
padding: 20px;

}

****

# **Java Script**
Sudo code:
write what you are trying to achieve before coding which can help you think out the prolem you need to solve


"use strict";

console.log("yo"); - to make sure js is linked to page. 

let points = 0;

welcome message

alert("welcome to my game");

ask user for name

let user = prompt("whats your name");

response  could be string, null, empty string
if user is an empty string or null, keep asking for name
empty string and null are falsy values, so if user is false ask fror their name.
i will need to loop that runs untill the condition is not met
everytime the loop runs ask the question again
(!) esclamation mark is logical not - (user = false)

while(!user){
    user = prompt(" i asked you what your name is dum dum").toLowerCase();
}

falsy values:
null -absence of value
undefined - variable that hasn't been assigned a value
false - boolean value
nan - not a number
0 - the number 0
-0 - the negative 0
"" - an empty string including "" '' ``

!-- # this is the not equals comparison operator - !== 
if(user !== "chris"){
    alert("to badyour not a chris")
}

alert(" hi " + user + "! finally you worked out how to spell your own name")

let answer = prompt(" is my favourite food popcorn").toLowerCase();
console.log(answer)

****

## Arrays

arrays allow you to hold more than 1 value in a single variable.
Array indexes start from 0.
each item in an array is a named element
Arrays should be declares using const as they cannot be reassigned 
Arrays can be manipulated using a variety of array methods.
array methods looking at today:
.length - tells us the length of array
.push - adds an element to the end of the array
.pop - removes an element of the end of an array 
.unshift - adds an element to the start of an array
.shift - removes element from start of array
.indexOf - tells you the index of an array-->


seperate array with a comma,
const foodsChrisLikes = ["", 5, true, [], {} ]

const foodChrisLikes = ["pizza", "noodles", "tacos"]

can console log specific indexes with [first item = 0 then ascending]
console.log(foodChrisLikes[0]);
console.log(foodChrisLikes[1]);
console.log(foodChrisLikes[2]);
console.log(foodchrislikes.length);
console.log(foodChrisLikes);

more often than not the for loop is used to loop through an array

for(let i = 0; i < foodsChrisLikes.length; i++){
    console.log(foodsChrisLikes[i])
}

****
.push
foodschrislikes.push("steak")
console.log(foodschrislikes);

.pop
foodschrislikes.pop()
console.log(foodschrislikes);

.unshift
foodschrislike.unshift("chips")
console.log(foodschrislikes)

.shift
foodschrislikes.shift()
console.log(chrislikesfood);

.indexOf
let index = cfoodschrisLikes.indexOf("porridge");
console.log(foodsChrisLikes)