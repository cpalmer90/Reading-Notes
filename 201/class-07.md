# **_Class 7_**

---

## constructor functions.

---

_constructor function allows us to create objects with less code duplication._

_constructor function starts with a captial first letter_

set parameters
`function Kitten(name, interests, imgFileName){
this.name: "bob";
this.age = 0;
this.interests = interests;
this.imageUrl = "images/" + imgFileName;
}
when creating new object need to store in const variable.

##### _new - new instance _

    const bob = new Kitten()
    console.log(bob);

## _prototype method_

Kitten.prototype.generateAge = function(){
return randomAge(3,11) + "months";
};

    function randomAge (min, max){    return Math.floor(Math.random() * (max - min + 1) + min);
    }

`function Kitten(name, interests, imgFileName){
    this.name: "bob";
    this.interests = interests;
    this.imageUrl = "images/" + imgFileName;
    this.age = this.generateAge()
    }`

    prototype needs to happen before making new instances.

---

## **Tables**

#### html.

<table>
<tr><th>table heading </th></tr>
<tr><td> table data</td></tr>
</table>

### **java Script**

const table = document.createElement("table")
article.appendChild(table);

const headerRow = document.createElement("tr")
table.appendChild(headerRow)

const kidsHeaderCell = document.createElement("th")
kidsHeaderCell.textContent = "kids"
headerRow.appendChild(kidsHeaderCell);

const kidsData = document.createElement("td")
kids.textContent = this.isGoodWithKids;
table.appendChild(kidsData);

const image = document.createElement("img")
image.setAttribute("src", this.imageUrl)
image.setAttribute("alt", `${this.name} profileshot.`)
article.appendChild(image);

---

### _styling a table_

table,th,td{
border:1px solid black;
border-collapse: collapse;
}

table{
margin-bottom: 1rem;
}
