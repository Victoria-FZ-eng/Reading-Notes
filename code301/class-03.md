# Passing Functions as Props

## React Lists and Keys

`<array.map()>` returns a new array with the same length.

ex. 

```
const numbers = [1, 2, 3, 4, 5];
const doubled = numbers.map((number) => number * 2);
console.log(doubled);
```
this will log [2, 4, 6, 8, 10] to the console.


***Each list item needs a unique KEY.***

*whwy do we use keys* ;because they help React identify which items have changed, are added, or are removed. 

## The Spread Operator

The Spread operator lets you expand an iterable like an object, string, or array into its elements while the Rest operator does the inverse by reducing a set of elements into one array.

like it can help in :Copying an array ,Concatenating or combining arrays, Using Math functions, Using an array as arguments, and so many other things (check references for more information).

example:

```
//example1
const cars = ['🚗', '🚙'];
const trucks = ['🚚', '🚛'];
const combined = [...cars, ...trucks];
// Result
// [ '🚗', '🚙', '🚚', '🚛' ]

//example 2
setTheArray([...theArray, newElement]);

//example 3
let person = {
    firstName: 'John',
    lastName: 'Doe',
    age: 25,
    ssn: '123-456-2356'
};


let job = {
    jobTitle: 'JavaScript Developer',
    location: 'USA'
};

let employee = {
    ...person,
    ...job
};

console.log(employee);
```

## Passing Functions between Components

In react we can pass functions through components using `state` and adding methods to the class.


#####  Things I want to know more about

Lifting state up.

References :
* [Lists & Keys](https://reactjs.org/docs/lists-and-keys.html) .
* [The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab) .
* [Passing Functions between Components](https://www.youtube.com/watch?v=c05OL7XbwXU)
* [Introduction](https://reactjs.org/tutorial/tutorial.html) .
* [Lifting State Up](https://reactjs.org/docs/lifting-state-up.html).