# faulity calulator

1. We can gerate a random number range from 0 to 1 using **Math.random()** Method and can store in variable like 

    let random = Math.random();

2. We can take a text(numbers are allowed and operation) input through a built in function present in window object i.e  **prompt()** through a dialog box . and There are different way to call prompt function

    
    prompt()
    prompt(message)
    prompt(message, defaultValue)



3. We can show the message through a dialog box using **alert()** built function . use for The alert dialog should be used for messages which do not require any response on the part of the user

    alert()
    alert(message)


4. Can create a **object** by self like for instance

**For accesing the value , we require key-name and object name** 

    object-name[key-name] will give the value present at given key!

### using {}

    const person = {};

    // Add Properties
    person.firstName = "John";
    person.lastName = "Doe";
    person.age = 50;
    person.eyeColor = "blue";


### using new Object()

    // Create an Object
    const person = new Object();

    // Add Properties
    person.firstName = "John";
    person.lastName = "Doe";
    person.age = 50;
    person.eyeColor = "blue";

### equvalent to 

    let person = {
        
        firstname:"john",
        lastname:"Doe",
        age:50,
        eyeColor:"blue",
    }

### For creating multiple object with same properties

1. Create a object type constructor function 

function Person(first, last, age, eye) {

  this.firstName = first;
  this.lastName = last;  // this has no value untill it passed
  this.age = age;
  this.eyeColor = eye;
}


2. making a type 

    const myFather = new Person("John", "Doe", 50, "blue");
    const myMother = new Person("Sally", "Rally", 48, "green");