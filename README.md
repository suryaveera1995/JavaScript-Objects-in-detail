# JavaScript-Objects-in-detail

What is an `Object`?<br/>
An object is an unordered list of primitive data types (and sometimes reference data types) that is stored as a series of name-value pairs. Each item in the list is called a property (functions are called methods).

Consider this object example:<br/>
`const myObj = {"firstName":"john", "lastName":"Doe"};`

An `Object` is a list of items. Each item contains a property or a method in the list.
The list is stored in key-value pair.

In the above `Object` the keys (or) properties are "firstName" and "lastName".
The values for the keys are "john" and "Doe" respectively.

### property names

The names of the properties can be a string or a number.

But there is a difference in accessibility of the property.

 * If property is a number, it has to be accessed with a bracket notation.

Below is the example to differenciate the notations of the properties and how to access them.

### example:
  
`const ageGroups = {10: "hundred", 20:"two hundred"};`<br/>
`console.log(ageGroups.10); // this will give a syntax error because the age froup is being accessed as a string`<br/>

`console.log(ageGroups["10"]);// output: "hundred"`

