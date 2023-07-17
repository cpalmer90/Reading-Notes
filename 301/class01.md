# JS Arrow Functions & Classes

---

<!-- class decleration -->

class Animal{}

<!-- class expression: annoymous but assigned to a variable -->

const Animal = class Animal{}

class Animal{
constructor(props) {
this.name = props.name;
this.color = props.color;
this.age = props.age;
this.sound = props.sound;

<!-- can be used to reduce code  -->

        **Object.assign(this, props)**

    }
    animalSpeak({
        console.log(this.sound);
    })

}

const wildAnimal = new Animal({name:"Tiger", color: "black and orange", age: 4, sound:"roar"});
console.log(wildAnimal);

wildAnimal.animalSpeak();

---

## Class inheritence.

class Dog extends Animal{
constructor(props, type){
super(props);
this.type = type
}
speak = ()=> {
console.log(`${this.name} barks`)
};
}

const Gary = new Dog ({name: "Gary", color:[white, red], age:10, sound:"woof"}, " Grizzly Bear");

---

## Arrow Functions.

function myName(name){
return `Hi my name is ${name}`
}

const theName = function(name){
return`what, my name is ${name}`
}

<!-- arrow function -->

const thatName = ()=>{
return `wow, check this out ${name}`;
};

const tree = name =>{}

---

# React
