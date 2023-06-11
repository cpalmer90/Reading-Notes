# ***java script***
****

what is java script - Java script makes your page dynamic. 
it can store and take action on that data. 

- Creating a javascript file.
- touch app.js

console - you can add java script directly into the console(it will not save but can be used to test)
right click on page and press inspect. 

Variables - is a container to store data and values. 

console.log(hisName) logs data to console. 

camel case is where first letter of first word is lowercase and first word of second word is a capital. 

****

## **Variables**

### 3 keywords to declare a variable  
1. var - outdated  
2. let - replaced var - used so you can change value of the code  
3. const - used to declare a constant value. a valuable that will not changed in the script.  

### examples:  
1. declare variable - var hisname = "rich" - Should avoid redeclaring the same variable.  
2. let myName = "chris" . when changing value you can use : myName = "replacement name".  
3. const herName = "sam" change - herName = "samantha" would then bring up an error and not allow you to change as it is a constant variable.  

linking variable to html - add  <script src= "app.js"> </script> to head (however it is not exclusive to head). 

****
#### Short cuts  
 - clg and press tab - creates console.log() 
- 

****

## **Data types** 

* string - because its in qoutes and uses characters (using number in a string eg. let petDetails = "my pet is " + myPetAge;)
console.log(typeof petDetails);  
* variable - data type is a number
*  boolean - let likesWalkies = true - uses true of false statments. 

other data types:
* Arrays
* objects

****

## arethemetic operators

* addition - let addition = 7 + 7;  console.log(addition)

* subtraction - let subtraction = 5 - 2;  console.log(subtraction)

* multiplication - let multiplication = 10 * 10;  console.log(multiplication)

* division - let divison = 15 / 3;  console.log(division)

let myNum = 5;
let thisNum = ++myNu;  console.log(thisNum)

let thatNum = --myNum;  console.log(thatNum)

**** 

## **comparison operators**  

* == -equal to "7" == 7
* > -greater than
* < -less than 
* >= -greater than or equal to
* <== -less than or equal to
* != -not equal
* !== -not equal value and not equal type 

****

## **Conditional statement** 

a conditional statement controls behaviours in javascript and determines whether or not a piece of code should run or not.  

*variable being used for example*
let myNum = 5

true - will run in console
if (myNum === 5) {
    console.log ("bingo");
}

False will not run
if(myNum === 4) {
console.log("flamingo");
}

#### if - else statement  
can make if statement use more logic - if (myNum === 6){
    console.log("you will win money");
} else {console.log("sucker");
}

****  

### Built in methods/prompts/document.write()


- prompt *variable changes from the users input*  
let userName = prompt("Hello User, Please tell me your name!");
console.log(userName)

- alert *doesnt have any fields for users to type will just bring up a message*
const welcomeMsg = alert("welcome to my page " + userName);

- *document.write()* is considered bad practice avoid using this where possible. 
 document.write(" Hello + userName + " thank you for visiting my site");

 - *Confirm* is The confirm() method displays a dialog box with a message, an OK button, and a Cancel button.

The confirm() method returns true if the user clicked "OK", otherwise false.


****

# *example*

// Types of variables

// var is the original way to declare a variable and you can declare it like this
var item1 = "Watch";
console.log(item1);

// let is the new way to declare a variable - 'let' variables can be re-assigned (changed)
let item2 = "Mouse";
console.log(item2);
// const is a variable that can't be changed - it's value remains constant and can't be re-assigned (changed)
const item3 = "Coca Cola";
console.log(item3);

// Types of data in JavaScript

//String (text)
("This is a string");

// Number
10;

// Boolean (true or false)
true;
false;

// Conditionals in JavaScript - comparing data to understand if they match

// Equals

// This uses double equals which only checks the value.
if (item2 == "Mouse") {
    console.log("Yeah, that's right");
}

if (0 == 0) {
    console.log("Yep, 0 is 0");
}

// Because we are using double equals it will run the console.log because it isn't fussy about one of them being a string and the other a number
if (0 == "0") {
    console.log("Yep 0 is '0', I dont care about the data type");
}

// This uses triple equals which checks the value and the data type. Below we are comparing two 0's but one is a string and one is a number. This means the console.log won't run.
if (0 === "0") {
    console.log(true);
}

// Does not equal

// This uses != which only checks the value
if (item3 != "Coca Cola") {
    console.log("Nah, thats coke mate");
}

if (0 != "0") {
    console.log("Thats not 0");
}

// This uses !== which checks the value and data type
if (0 !== "0") {
    console.log("Thats a zero but it's a string, not a number");
}

// More than or less than

// Less than comparsion
// This will run the console log if 0 is smaller than 1
if (0 < 1) {
    console.log("0 is smaller than 1");
}
// This won't run the console log because one is not smaller than 0
if (1 < 0) {
    console.log(false);
}

// More than comparison
// This will run the console log if 1 is greater than 0
if (1 > 0) {
    console.log("1 is greater than 0");
}
// This won't run the console log because 0 is not greater than 1
if (0 > 1) {
    console.log(false);
}

// Using a prompt
// This will ask 'Please tell me your name'
let username = prompt("Please tell me your name");

// This will ask the user to confirm their name
let confirmation = confirm("So I can call you " + username + "?");

// This will console log 'Hi username' if they click OK on the confirmation
if (confirmation == true) {
    console.log("Thanks, Hi " + username);
}

// This will console log 'Sorry, I got your name wrong' if they click cancel on the confirmation
if (confirmation != true) {
    console.log("Sorry, I got your name wrong");
} 

