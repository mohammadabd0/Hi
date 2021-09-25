# React Docs - Thinking in React

## What is the single responsibility principle and how does it apply to components?

Use the same methods to decide if a new function or object should be created. One such method is the notion of single accountability, which ideally means just one component is to do. It should be broken down into smaller subcomponents if it finishes growing.

## What does it mean to build a ‘static’ version of your application?

To build a static version of your app that renders your data model, you’ll want to build components that reuse other components and pass data using props. props are a way of passing data from parent to child. If you’re familiar with the concept of state, don’t use state at all to build this static version

## What are the three questions you can ask to determine if something is state?

- Is it passed in from a parent via props? If so, it probably isn’t state.

- Does it remain unchanged over time? If so, it probably isn’t state.

- Can you compute it based on any other state or props in your component? If so, it isn’t state.

# Higher-Order Functions

#### What is a “higher-order function”?

In Javascript, functions can be assigned to variables in the same way that strings or arrays can. They can be passed into other functions as parameters or returned from them as well. A “higher-order function” is a function that accepts functions as parameters and/or returns a function.

#### Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

Determine if two integers are true or false by comparing them.

#### Explain how either map or to reduce operates, with regards to higher-order functions?

The map method transforms an array by applying a function to all of its elements and then constructing a new array from the results. The resulting array will be the same length as the input array, but the function will have translated the information to a different form.
