# Putting it all together

## React Docs - Thinking in React

What is the single responsibility principle and how does it apply to components?

each componenet should perform on thing. If it grows it should be broken down into it's parts.

What does it mean to build a ‘static’ version of your application?

building a static model renders the data model, but has no interactivity. It makes sure you are render your data model correctly.

Once you have a static application, what do you need to add?

Making the UI interactive by changing the underlying data using state.

What are the three questions you can ask to determine if something is state?

Is it passed in from a parent via props? If so, it probably isn’t state.
Does it remain unchanged over time? If so, it probably isn’t state.
Can you compute it based on any other state or props in your component? If so, it isn’t state.

How can you identify where state needs to live?

you need to find the common owner or component that is higher up in the hierarchy that will own that state and be able to pass it down to it's children.

## Higher-Order Functions

What is a “higher-order function”?

functions that operate on other functions either by taking them as arguments or by returning them.

Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

this is using an arrow function that returns true is m > n and false if m < n

Explain how either map or reduce operates, with regards to higher-order functions.

it transforms an array by applying a function to each element and returns the result. Reduce uses a combining function and a start value. The array elements are passed through the combining function and passed back.
