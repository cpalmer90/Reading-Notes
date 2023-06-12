# **Programming with javascript**  
****

use strict will not allow you to use undefined variables.  
- "use strict";  

****

## **functions**  

Function declaration:  
Name of function    peramiters     function we want
function mySum      ()               {}

function mySum() {

let x = 2 + 2


}

you need to tell javascript to use the function *invoked* 

mySum();

Function command is hoisted up so even if you ivoke the function above the code it will still work. 


## *function expression*  

const myFunc = Function()
{ 

let x = 3 * 3;

 };

myFunc();

*function expression wont invoke if invoke code is above the script.*

## **perameters** 

function bestSum(param1, param2){

let x = param1 + param2

}

can put argument within the invoke 
bestSum(10, 10);

function theReturningSum(num1, num2, num3){

    let sum = num1 + num2;
    let sumDivided = sum / num3;

    return sumdivided;  - return the value of the function
}

console.log(theReturningSun(30, 30, 3));


function yourName(){

    let user = prompt ("what is your name?")
    return document.write(user);
}

function timeOfDay(){

let time = prompt ("what hour is it (0 -23)");
let message = ""

if (time <= 11>){
message = "good morning "
else if (time <= 18){
    message = "good afternoon"}


}

return document.write(time);

}

&& - mean and
|| - mean or


**** 

## *** Loops ***
Data type is an ARRAY 
index starts at 0.
let myPets = ["dog", "cat", "fish"] 
****

*initialization / condition/ increment*
these parts all happen in a loop function.

let myPets = ["dog", "cat", "fish"] 

for (let i = 0; i < myPets.length; i++){console.log("i love my pet " + myPets [i])
}


#### *while loop*

while condition(condition){

    statement
}

let n = 0
let x = 0

while(n < 3){
    n++;
    x += n;
    console.log(n);
    console.log(x);
}

if (x >= 3){

    break;
}

let answer

while(answer != 7){

    answer = prompt("guess a numer between 1 and 10")

    if (answer != 7){

alert("Try again")
    }
    else{alert("Woop Woop");
    }
}