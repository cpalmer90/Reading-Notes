# **CSS**  

****  

## Cascading style sheets.

to use css, need to make a css file. - in terminal ~ touch style.css

can include css in the head of the html file. 

can creat style elements (will take priority)
<h1 style="color: red">my logo</h1>

create a link element in head.  
<link rel="stylesheet" href="style.css"/>

Syntax for writting css: selectors   
*h1 {
color: red;
font-size: 30px;
}

* - universal selecter - selects most things on the page.  

type selector - h3 

class selecter - .hero-heading {
  color: pink;
}

give class to html element by going to html file and adding  class="hero-heading" inside the element. eh <h2 class="hero-heading> 


id selecter - # - #hero-heading {
  color: pink;
}

ID is unique, should be for one element.


 box-sizing: border-box;

nav li {} 

will target all nav with lists

nav > ul {

}

css properties that target text. - 

font-family: monospace;

can use google fonts. 

body{
  font-family: monospace;
  letter-spacing: 0.01em;
  line-height: 1.6;
  text-transform: uppercase;
  text-align: center;
}

ul {list-style: disc;
margin-left: 2rem;}

eric meyer css reset - https://meyerweb.com/eric/tools/css/reset/  
reset style must be before style sheet

 Border styling
section { border-width: 2px;
border-style: dotted;
border-color: red;
}

layout styles
section{



}
****
box model - 

margin  
border  
padding 
element 