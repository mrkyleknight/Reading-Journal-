# React and Forms



## React Docs - Forms

What is a ‘Controlled Component’?

*controlled component is a component that is controlled by React state*

Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

*depends on the specific requirements and desired user experience of the application. I would say when they submit, just in case they have corrections*

How do we target what the user is entering if we have an event handler on an input field?

*targeting the user's input using event.target.value*

## The Conditional (Ternary) Operator 

Why would we use a ternary operator?

*A ternary operator is used for concise conditional assignments or expressions in a single line of code.*

Rewrite the following statement using a ternary statement:

if(x===y){
  console.log(true);
} else {
  console.log(false);
}

*console.log(x === y ? true : false);*

Resources: 

https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff

https://legacy.reactjs.org/docs/forms.html
