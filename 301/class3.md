# Passing Functions as Props

## React Docs - lists and keys

What does .map() return?

it takes a value and puts it through a function that we define the return value of the function is what map gives back.

If I want to loop through an array and display each value in JSX, how do I do that in React?

use curly braces on the element that is being included in the JSX.

Each list item needs a unique ____.

key

What is the purpose of a key?

they identify what has changed, added, or removed.

## What is the spread operator?

List 4 things that the spread operator can do.

adding items to arrays, combining arrays, spreading an array out into a function's arguments, and copy an array.

Give an example of using the spread operator to combine two arrays.

`const one = [1,2,3] const two = [4,5,6]`
`cont three = [...one, ...two]`

Give an example of using the spread operator to add a new item to an array.

`const four = [7,8,9,...one]`

Give an example of using the spread operator to combine two objects into one.

`const objOne = {honk: "big"} const objTwo = {honk: "small"}`
`const objThree = {...objOne, ...objTwo}`

## How to Pass Functions Between Components

In the video, what is the first step that the developer does to pass functions between components?

using the state of the parent to pass different states from one componenet to the other.

In your own words, what does the increment function do?

modifies the state of the parent component and updates all components.

How can you pass a method from a parent component into a child component?

import the child componenet in the parent component and return it. Create some way to trigger that function.

How does the child component invoke a method that was passed to it from a parent component?

This works due to how class components. The child inherits the methods from the parent class since it "extends" it.
