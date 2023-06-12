
## *Branches*

****

to make a branch. 
git branch (then the name of branch you want to make)  

to move to new branch enter
git checkout (to name of branch)
ACP on branch - 
git add . 
git commit -m 'update'
git push -u origin (name of branch)

****  

display: inline- means the elements can be next to each other.  
margin 0 1rem  - top right bottom left- clockwise. 

body {
    max-width: 320px;
    font-size: 1rem;
    font-weight: 400;
    letter-spacing: 0.01em;
    line-height: 1.6;
    color: black;
    background-color: blanchedalmond;
}

* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

li {
    display: inline;
}

.container{
    width: 90%;
    margin: 0 auto;
}

.header-container {
    flex-direction: column;
}

media query
@media(min-width: 600px){

.header-container {
    flex-direction: row;
    justify-content: space-between;
    align-items: baseline;
}

a:hover {
    color:white;
}

****

let user;
let myFavColor;


alert("hi");

function userNamer({
    user = prompt("please tell me your name");
    alert("welcome to my site" + user)
}
)

username ();

function favColor(){
    color = prompt(user + "what is your favourite color?").toLowerCase()
    console.log(color)

    if (color === "red"){
        myFavColor = "green"
    } else if (color === "blue"){
        myFavcolor = "orange"
    } else {
        myFavcolor = "purple"
    }
    alert("nice" + color + " is a great color. my favourite color is "+ myFavColor);
}
favColor();
}