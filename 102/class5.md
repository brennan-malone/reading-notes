# Read: 05 - Design web pages with CSS

## What is CSS

* CSS is cascading style sheets
* used to make websites look great
* Using CSS you can control exactly how HTML elements look in the browser
* used for visual presentation styling
* browsers need to support a feature in order for it to function properly

### syntax  

h1 {  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; color: red;  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; font-size: 5em;  
}  

* the top h1 is a called a selector
* inside the braces is the declarations
* property value pairs
* different modules for CSS

## How to add CSS

three ways to insert CSS

1. external
2. internal
3. inline

* external styles are defined using the \<link rel="stylesheet" href="mystyle.css">
* Internal css uses the \<style> tag within the <\head> tag
* inline will be within the HTML element opening tag

### CSS Uses cascading order to determine style

## CSS Color

* RGB value color: rgb(220, 70, 0);
* RGBA value color: rgb(220, 70, 0, 0.5);
* HSL value color: rgb(90, 40%, 51%);
* Hex value color: #929292;

## CSS Reference

### Selectors

* Universal Selector *
* Tyle selector `elementname`
* Class selector `.classname`
* ID selector `#idname`
* Attribute selector `[attr=value]`

### Combinators

* Adjacent sibiling `A + B`
* General sibiling `A ~ B`
* Child `A > B`
* Descendant `A B`
* Column `A || B`

### Pseudo

* Pseudo classes :
* Pseudo elements ::

## Myers Web Reset Stylesheet

* a reset style sheet will reduce browser inconsistencies regarding default settings
* Good starting point but intentionally generic
* not a black box
* public domain and free to use

## Things I want to know more about

* how many reset stylesheets are there?
* is there different ones for differnt applications of CSS?
