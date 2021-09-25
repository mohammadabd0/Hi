# React and Forms

## What is a ‘Controlled Component’?

A controlled component is a component that renders form elements and controls them by keeping the form data in the component’s state.

- Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
  both of them will work, in the second way: when React is responsible for maintaining and setting its state. The state is kept in sync with the input’s value, meaning that changing the input will update the state, and updating the state will change the input.

## How do we target what the user is entering if we have an event handler on an input field?

after adding the setState on the ChangeInput function, we can target the event as event.target.value
The Conditional (Ternary) Operator Explained.

# Why would we use a ternary operator?

We use the ternary operator because it allows us to assgin one value to a variable that will return either true or false, also because it makes assigning values to variables easier to see and work with, because it's all on one line.

ex:

```js
if (x === y) {
  console.log(true);
} else {
  console.log(false);
}
```
