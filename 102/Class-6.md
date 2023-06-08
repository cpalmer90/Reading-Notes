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


*variable changes from the users input*  
let userName = prompt("Hello User, Please tell me your name!");
console.log(userName)



