# Problem Domain, Objects, and the DOM

## JavaScript Object Basics

### 1. How would you describe an object to a non-technical friend you grew up with?
A collection of information that is realted to each other. Name/D.O.B./adress.

### 2. What are some advantages to creating object literals?
It is easier to work with than an array, when you want to identify individual items by name.

### 3. How do objects differ from arrays?
you access an object's properties and methods using dot notation.

### 4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.
If an object property name is held in a variable, then you can't use dot notation to access the value, but you can access the value using bracket notation.

### 5. Evaluate the code below. What does the term this refer to and what is the advantage to using this?
If you create more than one single object literal, `this` enables you to use the same method definition for every object you create.
In the example below `this` would refer to 'Spot' and '14'.

const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}
## Introduction To The DOM

### 1. What is the DOM?
The Document Object Model (DOM) is a programming interface for web documents. You could call it the front end of stored infomation.

### 2. Briefly describe the relationship between the DOM and JavaScript.
The DOM is not a programming language, but without it, the JavaScript language wouldn't have any model or notion of web pages.