# What is a ‘call’?

A call is also known as function invocation.

# How many ‘calls’ can happen at once?

Only one function at a time

# What does LIFO mean?

Last In, First Out.

# Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

```js
first function = { console.log(first) }
second function = { // calling first fucntion first(); } // invoking second funtion which trigger the first second();
```

# What causes a Stack Overflow?

Stack over flow occurs when a loop is created through invoking a function, when it continues to call on it’s self, never resolving to a solution of final return
JavaScript error messages:

# What is a ‘refrence error’?

A reference error is using a variable that is not declared.

# What is a ‘syntax error’?

When something cant be parsed in terms of syntax. Errant curly brackets, () without closing them.

# What is a ‘range error’?

Range errors occur when we try and manipulate an object with some kind of legnth and is given an invalid length

# What is a ‘tyep error’?

Type errors occur when the code is expecting a certain data type in order to process it self, but does not recieve the data type expected.

# What is a breakpoint?

its something used in debugging
What does the word ‘debugger’ do in your code?
runs code up to a determined break point in order to test specific functions
