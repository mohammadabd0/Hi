# JavaScript Errors

- The try `statement lets you test a block of code for errors.

- The catch statement lets you handle the error.

- The throw statement lets you create custom errors.

- The finally statement lets you execute code, after try and catch, regardless of the result.

## JavaScript try and catch

The try statement allows you to define a block of code to be tested for errors while it is being executed.

The catch statement allows you to define a block of code to be executed, if an error occurs in the try block.

The JavaScript statements try and catch come in pairs:

```js
try {
  Block of code to try
}
catch(err) {
  Block of code to handle errors
}
```

## JavaScript Throws Errors

When an error occurs, JavaScript will normally stop and generate an error message.

The technical term for this is: JavaScript will throw an exception (throw an error).

JavaScript will actually create an Error object with two properties: name and message.

## The throw Statement

The throw statement allows you to create a custom error.

Technically you can throw an exception (throw an error).

The exception can be a JavaScript String, a Number, a Boolean or an Object:

```js
throw "Too big"; // throw a text
throw 500; // throw a number
```

If you use throw together with try and catch, you can control program flow and generate custom error messages.

# Debugging in JavaScript

As you might already know, there are broadly two categories of bugs: logical (errors of thought in function and/or utility) and syntactical (errors in translating thoughts to code). Examples of logical errors are when you square a number when you really meant to cube it, or when you use a variable or call a function that you did not intend to. Examples of syntactical errors are when you forget to place curly braces around a for loop or if you missed out a semicolon to terminate a JavaScript statement. The first category is much more difficult to deal with as compared to the latter. The process of removing or correcting errors in the code is called debugging. There are several ways to debug your code. Let's look at some of the most common ways to do this.

# Debugging using Error messages

JavaScript automatically points out many syntactical errors by printing out error messages. When you execute your code, the printed error message will point to a specific line of code. The error description will give you a fair idea of what could be wrong and usually all you need is a simple correction to remove the bug. As an example, say you have a JavaScript file called test.js with the following line of code.
