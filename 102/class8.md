# Read: 08 - Operators and Loops

## Expressions and Operators

* two types of expressions

1. Purely evaluate
2. have side effects

* Usually pure evaluation is due to a mistake because evaluation Doesn't produce any effects
* Javscript has binary operators, unary operators, and one ternary operator
* inifx is when an operator is placed between two operands all binary operators in javascript are infix
* unary can either be prefix or post fix like i++ or ++i
* Javascript ++ and -- are postfix all others are prefix
* it is an error to assign values to unmodifiables properties or properties of an expression without null or undefined
* if you mirror an array or object literal syntax you are able use destructure assignment

### Example of destructuring

// without destructuring  
const one   = foo[0];  
const two   = foo[1];  
const three = foo[2];  

// with destructuring  
const [one, two, three] = foo;

* Assignments can be nested
* the resulting values are always based on the operands before the expression
* avoid assignment chains because they can result in suprises

### Comparision Operators

* == equal to
* === equal value and equal type
* != not equal
* !== not equal value or not equal type
* \> greater than
* < less than
* \>= greater than or equal to
* <= less than or equal to
* ? ternary operator

## Loops

* great way to do something repeatedly

1. for loop
2. do while
3. while

* for (initialexpression; conditionexpression; increment expression) statement
* do while repeats until specificed condition evaluates to false
* While as long as a specific condition evaluates to true
* if the condition becomes false it passes the statement.
* to execute multiple statements use {} to group those statements
* label provides a statement with an identifier that lets you refer to it elsewhere in the program
* break statement will terminate the loop
* break; or break label
* the continue statement can restart a while, do while, for, or label statement.

## Things I want to know more about

* Nullish coalescing assignment? What is that?
