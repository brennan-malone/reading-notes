# Read: 01 - Getting Started

## Getting Started

### Good starting table of contents

[MDN site with starting a webpage documents](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web)

## How the web Works

* Client and server architecture
* client sends request
* server sends response
* TCP/IP is the internet transmission protocol
* DNS is address book for websites
* HTTP is formmating language for client/server applications
* Compenet files are what makes up the website "the goods"

### Steps in process

1. Browser finds address in DNS server
2. Browser sents an HTTP request asking for a copy of website using TCP/IP
3. If approved sents 200 or appoval message, then starts sending compenent files
4. The browser assembles files and displays then in the browser

* Browsers parse HTML first
* any `link` elements require another request back to server
* generates an in-memory DOM tree from parsed HTML and a in-memory CSSOM structure from parsed CS.
* Browser builds DOM tree, applies CSSOM tree styles and executes JavaScript
* DNS is IP to human readable name

## Website Design and Process

1. what is your website about?
2. what information are you presenting?
3. what does your website look like?

### Assets

* Text
* Color/Theme Color
* Images
* Font
* all things to consider when designing a site

## JavaScript Basics

* JavaScript is great for interactivity on a website
* Compact yet flexible
* JavaScript allows APIs for increased functionality
* Third-party frameworks and libraries
* Can use `querySelector()` to grab a reference from the DOM API

### JS Core Features

* Variables, case sensitive
* let, cosnt, var
* string, number, boolean, array, object
* `/* something commented */`

### Reading questions answered pt. 1

1. Compose a short poem describing how HTTP sends data between computers.
   * O HTTP! my HTTP! our fearful trip is done  
   The packets has weather'd every rack, the page we sought is here,  
   The port is near, the html I hear, the user all exulting,  
   While follow eyes the steady files, the page large and scrolling;  
   But O HTTP! HTTP! HTTP!  
   O the error 504,
   where on my screen the dead page lies
   A bad request cold and dead.  
2. Describe how HTML, CSS, and JS files are “parsed” in the browser.

   * Browsers parse HTML first
   * any `link` elements require another request back to server
   * generates an in-memory DOM tree from parsed HTML and a in-memory CSSOM structure from parsed CS.
   * Browser builds DOM tree, applies CSSOM tree styles and executes JavaScript

3. How can you find images to add to a Website?
   * You can use free to use image sites such as unsplash.com or others. Download the image and include it as an asset
4. How do you create a String vs a Number in JavaScript?
   * Use a variabel declaration such as `let myString = 'hi'`
   * a string is created using ' or " a number is simply 1 or 923 whatever the number is
5. What is a Variable and why are they important in JavaScript?
   * A variable is a way to store a value. They are important in all programming because they allow for repeated functionality and operation depending on a value.

## Getting started with HTML

* HTML just structures content it is a way to mark content a certain way
* HTML will contain tags and that tells the browser to render content a certain way

Main parts of an element are

1. opening tag
2. closing tag
3. the content
4. the element

void elements have not content and therefore no closing tag

some HTML elements are

* h1
* img
* p
* div
* ul
* li
* a

## HTML Document Structure

* Standard webpage componenets
* header
* nav bar
* main content
* sidebar
* footer

* good idea to use the right HTML elements for the job due to semantic value
* HTML should be coded to represent the data, not for the default styling
* Helps with SEO influence

some semantic elements

* \<article\>
* \<aside\>
* \<details\>
* \<figcaption\>
* \<figure\>
* \<footer\>
* \<header\>
* \<main\>
* \<mark\>
* \<nav\>
* \<section\>
* \<summary\>
* \<time\>

non semantic elements

* \<div>
* \<span>

## Metadata in HTML

* head is the metadata in HTML
* UTF 8 contains all characters from any human language good idea to set
* name specifies the type of meta element it is; what type of information it contains.
* content specifies the actual meta content.
* can include keywords that have the ptential to make page appear higher in relevant searches or SEO

A favicon can be added to your page by:

* Saving it in the same directory as the site's index page, saved in .ico format
* Adding the following line into your HTML's \<head> block to reference it
* script element should go in the head and always include a src and `defer` so HTML fully loads and doesn't cause issues
* you should also use a link to stylesheets for your css file
* you should set the language of your page `<html lang='en-US'>`

### Reading questions answered pt. 2

1. What is an HTML attribute?
   * an HTMl attribute is some property of an HTML element usually some display property
2. Describe the Anatomy of an HTMl element.
   * opening tag, closing tag, content, element
3. What is the Difference between \<article> and \<section> element tags?
   * A section means just a section of content, where an article is a larger textual content
4. What Elements does a “typical” website include?
   * Standard webpage componenets
   * header
   * nav bar
   * main content
   * sidebar
   * footer
5. How does metadata influence Search Engine Optimization?
   * keywords and descriptions are part of what search engines search for and can be optimized
6. How is the \<meta> HTML tag used when specifying metadata?
   * it is used to give a description and name to the data and page specifically for the contents within a page without having to look at the page

## How to start to design a website

* what do you want to accomplish?
* how will a website help me reach my goals?
* what needs to be done, and in what order, to reach my goals?

* make a prioritized list of goals
* make a rough plan on what to do. Have an idea

### Reading questions answered pt. 3

1. What is the first step to designing a Website?
   * project ideation
2. What is the most important question to answer when designing a Website?
   * what exactly do you want to accomplish?

## semantics

* The meaning of a piece of code
* should use if applicable

### Reading questions answered pt. 4

1. Why should you use an \<h1> element over a \<span> element to display a top level heading?
   * you should always use the right semantic element for the right job this is not only good practice but helps us leverage added in benefits of the semantic elements
2. What are the benefits of using semantic tags in our HTML?
   * SEO
   * Screan readers
   * finding meaning for other coders
   * suggests the type of data that should be there
   * mirrors proper element/componenet naming

## What is JavaScript?

* helps display more than static information
* core client side javascript is what is being discussed
* store variables
* oeprations on text
* running code when certain events happen
* APIs are read-made sets of code that allow for advanced development in a simple application method
* two categories
* Browsers APIs
* Each tab has its own bucket for running code
* runs top to bottom
* interpreted programming language
* two methods async and defer
* async will download the script without blocking the page, once it is downloaded the script executes
* defer not run until all page content has been loaded

### Reading questions answered pt. 5

1. Describe 2 things that require JavaScript in the Browser?
   * APIs and event listeners
2. How can you add JavaScript to an HTML document?
   * using the script tag

## Questions

No questions
