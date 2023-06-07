# Passing Functions as Props

What does .map() return?

*map() function to take an array of numbers and double their values.*

If I want to loop through an array and display each value in JSX, how do I do that in React?

*You use the map() method, to loop through an array and render each value in JSX.*

Each list item needs a unique ____.

*key*

What is the purpose of a key

*Optimizing rendering and reconciliation*

*Preserving component state*

## The Spread Operator

What is the spread operator?

*spread syntax refers to the use of an ellipsis of three dots (…) to expand an iterable object into the list of arguments.*

List 4 things that the spread operator can do.

*Copying an array,
Concatenating or combining arrays,
Using Math functions and
Using an array as arguments*

Give an example of using the spread operator to combine two arrays

*const array1 = [1, 2, 3];
const array2 = [4, 5, 6];

const combinedArray = [...array1, ...array2];

console.log(combinedArray);*

Give an example of using the spread operator to add a new item to an array.

*const array1 = [1, 2, 3];
const newItem = 4;

const newArray = [...array1, newItem];

console.log(newArray);*

Give an example of using the spread operator to combine two objects into one.

*const obj1 = { name: 'John', age: 25 };
const obj2 = { occupation: 'Developer', city: 'New York' };

const combinedObj = { ...obj1, ...obj2 };

console.log(combinedObj);*

## How to Pass Functions Between Components

In the video, what is the first step that the developer does to pass functions between components?

*pass functions between components in a component-based framework like React*

In your own words, what does the increment function do?

*The increment function increases a value by a specified amount.*

How can you pass a method from a parent component into a child component?

*you can pass the method as a prop to the child component.*


How does the child component invoke a method that was passed to it from a parent component?

*invoke a method that was passed to it from a parent component, it can simply call the method by accessing it through the props object using the appropriate prop name.*


resources: 

https://legacy.reactjs.org/docs/lists-and-keys.html

https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab

https://chat.openai.com/
