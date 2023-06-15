# Class 2
****
## Headings.
headings run from 1-6 *h1* is the most important and you can only have one on a page. you can use h2-6 as many times on a page as you would like.  
****
## paragraph. 
 can type lorem followed by a number to fill a paragraph. 
<p></p> elements are for writing paragraphs on page. 

****
## lists.
 - ordered list - <ol> numbered </o>  
 - unordered list - <ul> dotted </ul>
 both lists require list items <li></li> within them. 

 ****

 Javascript - 

 Using strict - 
 
 *confirm either returns true or false*
 let answer1 = confirm(" Are you ready to roll");
 console.log(answer1);

 if (answer1 === true) {
    consol.log("yay");
 } else {
    console.log("nay");
 }


 ****
**boolean variables**
 let first = true;
 let second = true;
 let third = true;
*when we use the && (and) operator both conditions must be true*  
*when we use the || (or) only one condition has to be true*

 if(first && third){
    console.log("first and thirs were true");
 } else if (first || )
****

 ## switch statement. 
 *when javascript reaches a break keywokrd, it breaks out of the switch block*
 *this will stop the execution inside the switch block*
 *it is not neccessary to break the last case in a switch block the block breaks 
 (ends) there anyway.*

 *the switch expression iss evaluated once. *
 *the value of the expression is compared with the values of each case*
 *if there is a match the associated block of code is executed*
 *if there is no match the default block of code is executed. *

 let color = prompt("what is your favourite colour")

 switch(color.toLowerCase()){
    case "red";
    console.log(your favourite colour is red");
break;
case"blue;
console.log("your fav color is blue");
break;
default:
condsole.log("no idea what that is"); }

****
