
# State and Props

## React Lifecycle

Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

*Render*

What is the very first thing to happen in the lifecycle of React?

*Mounting, an instance of a component is being created and inserted into the DOM.*

Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

*Constructor, Render, componentDidMount, React Updates and componentWillUnmount*

What does componentDidMount do?

*invoked immediately after a component is mounted and is a good place to set up any subscriptions*

## React State Vs Props

What types of things can you pass in the props?

*any data type*

What is the big difference between props and state?

*State is controlled by react components and Props are controlled by whoever renders the components*

When do we re-render our application?

*When the application needs to update the app with some new data*

What are some examples of things that we could store in state?

*user input, application data, and UI state* 

Resources:

https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093


https://www.youtube.com/watch?v=IYvD9oBCuJI

https://refine.dev/blog/react-props/#:~:text=We%20can%20pass%20any%20data,%2C%20string%2C%20function%2C%20etc.&text=Yes%2C%20it%20is%20possible%20to,display%20the%20object's%20property%20values.