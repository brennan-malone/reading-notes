# In memory storage

## Understanding the JavaScript Call Stack

What is a ‘call’?

A function invocation.

How many ‘calls’ can happen at once?

one at a time.

What does LIFO mean?

last in first out. like a stack of plates.

Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

`function first() {`
  `do something`
`}`

`function second() {`
  `first()`
`}`

What causes a Stack Overflow?

occurs when the function goes over the maximum stack calls that it can accomodate.

## JavaScript error messages

What is a ‘reference error’?

try to use a variable that is not yet declared.

What is a ‘syntax error’?

occurs when you have something that cannot be parsed in terms of suntax.

What is a ‘range error’?

try to manipulate an object with some kind of length and give ti an invalid length.

What is a ‘type error’?

error shows up when the types you are trying to use or access are incompatible like accessing a property in an undefined type.

What is a breakpoint?

lets you check what happens before that line and you can evaluate what happens after.

What does the word ‘debugger’ do in your code?

debugger stops the execution of javascript and calls the debugging function.
