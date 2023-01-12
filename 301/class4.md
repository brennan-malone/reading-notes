# React and Forms

## React Docs - Forms

What is a ‘Controlled Component’?

it is a form whose value is controlled by React. This is done by the component that renders a form also controls what happens in that form on user input.

Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

we should update the state with thier responses as they type them.this is because the input value is driven by the React state and we can then pass that value to other UI elements or reset it from other event handlers.

How do we target what the user is entering if we have an event handler on an input field?

set state to the event target value. Using an event handler in the constructor.

## The Conditional (Ternary) Operator Explained

Why would we use a ternary operator?

We use the ternary operator to simplify if statements that we need to write. Provides a more concise way to write true/false conditionals.

Rewrite the following statement using a ternary statement:

`x===y ? console.log(true) : console.log(false)`
