# Semantics HTML / Wireframes / CSS
****

Wireframes - 

outline of a page you want to make. structure and layout. 

low fidelity wireframe - very basic simple. 

****

new repo - html-sem - public - readme- create.

make sure to select ssh - copy code -  
open terminal - pwd - ls - cd into directory- git clone [paste code here]   
cd into new repo - git code . to open vsc.  
complete README.md to discribe what project is about and what it needs to work.  

open terminal - touch index.html - Index.html is important and always needs top be in the project.  

open index - press ! to fill out infomation required in an html file.  

tells browser what doc type to expect
`<!DOCTYPE html>`

specifify language expected is english
`<html lang="en">`

Head element is container for meta data. data about data.
`<head></head>`


covers most characters in the world
`<meta charset="UFt-8"/>`

gives the device infomation about how page will be seen on the current device. 
`<meta name="viewport" content="width=device-width, initial-scale=1.0"/>`


nest in head good for visability
`<title> document title</title>`

Nest in head
`<meta name="description" content"this is a website" />`

Body where html will go - what user will see `<body></body>  

main content of page
<main></main>  

semantic HTML -  

* tags that are semantic  
    *  


division of space  
<div></div>  

Span <span> </span>  


self contained infomation, such as blog posts. 
<article>

indirectly related to page infomastion. side bar.
<aside>


HTML  
<head>   
meta data goes here. 
</head>  

<body>  

<header>
  <h1>logo</h1>
  <nav> 
    <ul>
        <li><a href="link to page">user sees this info</a></li>
        <li></li>
        <li></li>
    </ul>
  </nav>
</header>  

<main>  

<section>
<img src="" alt="">
<h2>hero heading</h2>
<p>lorem 20</p>
</section>

<section>
 <article></article>
 <article></article>
 <article></article>
</section>

<aside>
 <section>
 <h3> title</h3>
 <article></article>
 <article></article>
 <article></article>
 </section>


 <section></section>
 <section></section>
</aside>

</main>  

</body>

<footer>

<p>&#169 chris</p>

</footer>

****


# **CSS**  

****  

Cascading style sheets.

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


<!-- box-sizing: border-box; -->

nav li {} 
<!-- will target all nav with lists -->
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

<!-- eric meyer css reset - https://meyerweb.com/eric/tools/css/reset/  
reset style must be before style sheet  -->

<!-- Border styling -->
section { border-width: 2px;
border-style: dotted;
border-color: red;
}

<!-- layout styles -->
section{



}

box model - 

margin  
border  
padding 
element 