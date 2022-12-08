# Read: 09 - Forms and JS events

## HTML Forms

1. Why are forms so important in web development?
   * They are an essential way to collect data from a user and submitting that data to a server.
2. When designing a form, what are some key things to keep in mind when it comes to user experience?
   * A big piece of the design from an accessability stand point is to use a label for each element and use fieldset to describe possible options.
   * It is recommended not to use a reset button from a UX design perspective.
3. List 5 form elements and explain their importance.
   1. \<input> allows us to set or return or set a value of a text input field
   2. \<label> this is a critical piece of all forms and should be used with for to describe the form it is for
   3. \<textarea> a multi-line plain-text editing control, good for when a user should enter a sizeable amount of free-form text
   4. \<select> provides a menu of options to select from
   5. \<button> interactive element that when activated performs some programmable action

## Introduction to events

1. How would you describe events to a non-technical friend?
   * I would describe an event as simply something that happens on a web page that you can react to programmatically.
2. When using the addEventListener() method, what 2 arguments will you need to provide?
   * The name of the event we want to register this handler for and the code that comprises the handler function we want to run.
3. Describe the event object. Why is the target within the event object useful?
   * It helps with nested events when you want something to happen even when you activate it on its parent
4. What is the difference between event bubbling and event capturing?
   * Event bubbling starts on the inner most nested event and bubbles upwards and event capturing works exactly the opposite started at the least most nested and going down.

## Things I want to know more about

Event delegation in practice
