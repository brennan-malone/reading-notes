# Read: 03 - HTML Lists, Control Flow with JS, and the CSS Box Model

## Learn HTML

1. When should you use an unordered list in your HTML document?
   * if the order of the list items is not meaningful and can be changed
2. How do you change the bullet style of unordered list items?
   * use the `type` attribute with the bullet style desired circle, disc, square
3. When should you use an ordered list vs an unorder list in your HTML document?
   * if the order of the list items is meaningful and cannot be changed
4. Describe two ways you can change the numbers on list items provided by an ordered list?
   * using reversed and start

## The box model

1. Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?
   * The padding would be a supporting character directly interacting with the content or main character
   * The margin is outside the border and does not interact with the content directly more of a ancillary character
2. List and describe the four parts of an HTML elements box as referred to by the box model.
   * content box
   * padding box
   * border box
   * margin box
  
## Learn JS

1. What data types can you store inside of an Array?
   * you can store any data type within an array, numbers, strings, boolean, characters, objects.
2. Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?
   * yes it is valid to store an array inside of another array, it is called a multidemensional array
   * to access the values stored call the array name with the associated index such as `people[2][0]` will access the value of Bill
 `const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];`
3. List five shorthand operators for assignment in javascript and describe what they do.
   * Addition assignment `x += f() x = x + f()` adds the value of f() to x and assigns that new value to x
   * Subtraction assignment `x -= f() x = x - f()` subtracts the value of f() to x and assigns that new value to x
   * Multiplication assignment `x *= f() x = x * f()` multiplies the value of f() to x and assigns that new value to x
   * Division assignment `x /= f() x = x / f()` division the value of f() to x and assigns that new value to x
   * Remainder assignment `x %= f() x = x % f()` find the remainder of f() to x and assigns that new value to x
4. Read the code below and evaluate the last expression and explain what the result would be and why.

   * `let a = 10;`  `let b = 'dog';`  `let c = false;` `// evaluate this` `(a + c) + b;`

   * The expression would evaluate to 10dog because (10 + false) will equal 10 and then 10 + dog will coerce the number into a string and concatenation means the final product will be 10dog.

5. Describe a real world example of when a conditional statement should be used in a JavaScript program.
   * a good real world example of a conditional statement is when you only want to perform an function if a value is smaller than another. For example do func() if X is less than Y if not don't do anything
6. Give an example of when a Loop is useful in JavaScript.
   * A loop is great when something needs to be done over and over again say iterating over a array x numbers of times. Why do them individually when youcan just use a loop

## Things I want to know more about

What is a good example of a real world bitwise operator
