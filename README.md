# JavaScript Interview Questions 🎯

JavaScript stands as a versatile language, powering interactive web experiences and extending its influence into full-stack development with frameworks like Node.js. Its broad community support and rich ecosystem make it a rewarding skill in the tech industry.

In this document, you'll find a compilation of commonly asked JavaScript interview questions along with detailed explanations.

## Table of Contents

1. [What is JavaScript?](#1-what-is-javascript)
2. [Data Types in JavaScript](#2-what-are-the-data-types-in-javascript)
3. [Difference between null and undefined](#3-what-is-the-difference-between-null-and-undefined)
4. [DOM in JavaScript](#4-what-is-the-dom-in-javascript)
5. [Event in JavaScript](#5-what-is-an-event-in-javascript)
6. [Anonymous Function](#6-what-is-an-anonymous-function-in-javascript)
7. [Closures in JavaScript](#7-what-are-closures-in-javascript)
8. [== vs === in JavaScript](#8-what-is-the-difference-between--and--in-javascript)
9. [Hoisting in JavaScript](#9-what-is-hoisting-in-javascript)
10. [The `this` Keyword](#10-what-is-the-this-keyword-in-javascript)
11. [Ways to Define a Function](#11-what-are-the-different-ways-to-define-a-function-in-javascript)
12. [The `let` Keyword](#12-what-is-the-purpose-of-the-let-keyword-in-javascript)
13. [The `const` Keyword](#13-what-is-the-purpose-of-the-const-keyword-in-javascript)
14. [Template Literals](#14-what-are-template-literals-in-javascript)
15. [JavaScript Promises](#15-what-are-javascript-promises)
16. [Async/Await Syntax](#16-what-is-the-asyncawait-syntax-in-javascript)
17. [Arrow Functions](#17-what-are-arrow-functions-in-javascript)
18. [Event Delegation](#18-what-is-event-delegation-in-javascript)
19. [The `map()` Function](#19-what-is-the-purpose-of-the-map-function-in-javascript)
20. [The `filter()` Function](#20-what-is-the-purpose-of-the-filter-function-in-javascript)
21. [The `reduce()` Function](#21-what-is-the-purpose-of-the-reduce-function-in-javascript)
22. [Callback Functions](#22-what-is-a-callback-function-in-javascript)
23. [Difference between `let` and `var`](#23-what-is-the-difference-between-let-and-var-in-javascript)
24. [JavaScript Modules](#24-what-are-javascript-modules)
25. [Object Destructuring](#25-what-is-object-destructuring-in-javascript)
26. [JavaScript Classes](#26-what-are-javascript-classes)
27. [Inheritance in JavaScript](#27-what-is-inheritance-in-javascript)
28. [Getters and Setters](#28-what-are-javascript-getters-and-setters)


---

## 1. What is JavaScript?

JavaScript is a high-level, interpreted programming language primarily used for adding interactivity to web pages.

## 2. What are the data types in JavaScript?

JavaScript has six primitive data types: string, number, boolean, null, undefined, and symbol, along with a complex data type called object.


## 3. What is the difference between null and undefined?

`null` represents the intentional absence of any object value, while `undefined` indicates the absence of a value or an uninitialized variable.

## 4. What is the DOM in JavaScript?

The Document Object Model (DOM) is a programming interface that represents the structure of HTML and XML documents. It allows JavaScript to access and manipulate the content and structure of a webpage.

## 5. What is an event in JavaScript?

An event is an action or occurrence that happens in the browser, such as a button click or page load. JavaScript can respond to these events by executing code in response.

## 6. What is an anonymous function in JavaScript?

An anonymous function is a function without a name. It can be assigned to a variable or passed as an argument to another function. They are often used for one-time or callback functions.

## 7. What are closures in JavaScript?

Closures are functions that have access to variables from an outer function, even after the outer function has finished executing. They encapsulate data and provide a way to maintain state between function calls.

## 8. What is the difference between == and === in JavaScript?

The `==` operator checks for equality after performing type coercion, while the `===` operator checks for equality without type coercion, ensuring both the value and type match.

## 9. What is hoisting in JavaScript?

Hoisting is a JavaScript behavior where variable and function declarations are moved to the top of their containing scope during the compilation phase, allowing them to be used before they are declared.

## 10. What is the this keyword in JavaScript?

The `this` keyword refers to the object that is currently executing the code. Its value is determined by how a function is called, and it provides a way to access object properties and methods within a function.

## 11. What are the different ways to define a function in JavaScript?

Functions in JavaScript can be defined using function declarations, function expressions, arrow functions, and methods within objects.

## 12. What is the purpose of the let keyword in JavaScript?

The `let` keyword is used to declare block-scoped variables in JavaScript. Variables declared with `let` are only accessible within the block where they are defined.

## 13. What is the purpose of the const keyword in JavaScript?

The `const` keyword is used to declare block-scoped variables in JavaScript that cannot be re-assigned. However, it does not make objects or arrays immutable.

## 14. What are template literals in JavaScript?

Template literals, denoted by backticks (\`), are a way to create strings in JavaScript that support interpolation of variables and multi-line strings.

## 15. What are JavaScript promises?

Promises are used for asynchronous programming in JavaScript. They represent the eventual completion (or failure) of an asynchronous operation and allow chaining of operations using `.then()` and `.catch()`.

## 16. What is the async/await syntax in JavaScript?

The async/await syntax is a modern approach to handle asynchronous operations. It allows writing asynchronous code in a more synchronous-like manner, making it easier to read and maintain.

## 17. What are arrow functions in JavaScript?

Arrow functions are a concise syntax for defining functions in JavaScript. They have a shorter syntax compared to traditional function expressions and inherit the `this` value from the enclosing scope.

## 18. What is event delegation in JavaScript?

Event delegation is a technique where you attach an event listener to a parent element instead of individual child elements. It allows handling events efficiently, especially for dynamically added elements.

## 19. What is the purpose of the map() function in JavaScript?

The `map()` function is used to create a new array by applying a given function to each element of an existing array. It allows transforming and manipulating array elements easily.

## 20. What is the purpose of the filter() function in JavaScript?

The `filter()` function is used to create a new array containing elements that pass a certain condition defined by a provided function. It allows filtering elements from an array based on specific criteria.

## 21. What is the purpose of the reduce() function in JavaScript?

The `reduce()` function is used to reduce an array to a single value by applying a function to each element and accumulating the result. It is often used to perform calculations or transformations on arrays.

## 22. What is a callback function in JavaScript?

A callback function is a function that is passed as an argument to another function and gets executed at a later time or in response to an event. It enables asynchronous and event-driven programming.

## 23. What is the difference between let and var in JavaScript?

The `let` keyword declares block-scoped variables, while the `var` keyword declares function-scoped variables. Variables declared with `var` are hoisted, while variables declared with `let` are not.

## 24. What are JavaScript modules?

JavaScript modules are reusable pieces of code that encapsulate related functionality. They allow for better organization, encapsulation, and code reuse in larger JavaScript applications.

## 25. What is object destructuring in JavaScript?

Object destructuring is a feature that allows extracting properties from objects and assigning them to variables. It provides a concise way to extract values and work with object properties.

## 26. What are JavaScript classes?

JavaScript classes are a way to define objects with shared properties and behaviors. They provide a template for creating multiple instances of objects with similar characteristics.

## 27. What is inheritance in JavaScript?

Inheritance is a mechanism in JavaScript where an object can inherit properties and methods from another object. It allows for code reuse and creating hierarchical relationships between objects.

## 28. What are JavaScript getters and setters?

Getters and setters are special methods used to get and set the values of object properties, respectively. They provide control over property access and enable data validation and encapsulation.

...

## 29. What is the spread syntax in JavaScript?

The spread syntax (`...`) is used to expand elements of an array or properties of an object. It provides a concise way to copy arrays, combine arrays, and create shallow copies of objects.

## 30. What is the fetch API in JavaScript?

The Fetch API is a modern interface for making HTTP requests in JavaScript. It provides a more flexible and powerful way to interact with servers and handle responses compared to older methods like XMLHttpRequest.

## 31. What is Local Storage and Session Storage in JavaScript?

Local Storage and Session Storage are web storage options provided by browsers to store key-value pairs persistently (Local Storage) or for the duration of a page session (Session Storage). They offer a convenient way to store data on the client side.

## 32. What is the difference between map() and forEach() in JavaScript?

Both `map()` and `forEach()` are methods used to iterate over arrays, but `map()` returns a new array based on the provided function, while `forEach()` simply executes the function for each array element without creating a new array.

## 33. What is the Event Loop in JavaScript?

The Event Loop is a fundamental concept in JavaScript that manages the execution of code. It continuously checks the call stack for functions to execute, the callback queue for functions to add to the call stack, and the web APIs for asynchronous events.

## 34. What is the purpose of the 'use strict' directive in JavaScript?

The 'use strict' directive is used to enable a stricter set of rules for JavaScript code. It helps catch common coding mistakes and prevents the use of certain error-prone features, promoting cleaner and more reliable code.

## 35. What is a Web Component in JavaScript?

Web Components are a set of web platform APIs that allow creating custom, reusable, and encapsulated HTML elements. They consist of four main specifications: Custom Elements, Shadow DOM, HTML Templates, and HTML Imports.

## 36. What is the difference between synchronous and asynchronous code execution?

Synchronous code executes line by line, blocking further execution until the current operation is completed. Asynchronous code allows the program to continue executing while waiting for an asynchronous operation to complete, improving efficiency and responsiveness.

## 37. What is the purpose of the XMLHttpRequest object in JavaScript?

The XMLHttpRequest object is used to interact with servers and retrieve data asynchronously. It is a foundational part of AJAX (Asynchronous JavaScript and XML) and is commonly used to update parts of a web page without requiring a full page reload.

## 38. What is the Event.preventDefault() method used for?

The `Event.preventDefault()` method is used to prevent the default behavior associated with an event. For example, preventing a form submission or a link click from triggering their default actions.

## 39. What is the difference between localStorage and sessionStorage?

localStorage and sessionStorage are both web storage options, but localStorage persists data even when the browser is closed and reopens, while sessionStorage only retains data for the duration of a page session.

## 40. What is the role of the 'defer' attribute in the `<script>` tag?

The 'defer' attribute in the `<script>` tag is used to defer the execution of the script until after the document has been parsed. This can improve page loading performance by allowing other elements to load first.

## 41. How does the 'async' attribute in the `<script>` tag differ from 'defer'?

The 'async' attribute also defers script execution, but it doesn't guarantee the order of script execution. Scripts with the 'async' attribute will be executed as soon as they are available, potentially out of order.

## 42. What is the Same-Origin Policy in JavaScript?

The Same-Origin Policy is a security measure in browsers that restricts web pages from making requests to a domain different from the one that served the web page. It helps prevent cross-site request forgery and other security vulnerabilities.

## 43. What is Cross-Origin Resource Sharing (CORS)?

Cross-Origin Resource Sharing (CORS) is a mechanism that allows servers to specify which origins are permitted to access their resources. It helps overcome the Same-Origin Policy restrictions for certain cross-origin requests.

## 44. What is the difference between call() and apply() methods in JavaScript?

Both `call()` and `apply()` are methods used to invoke a function with a specified 'this' value and arguments. The difference is in how additional arguments are passed; `call()` takes them as individual arguments, while `apply()` takes them as an array.

## 45. What is the Event Bubbling and Capturing in JavaScript?

Event Bubbling and Capturing are two phases of event propagation in the DOM. Bubbling occurs from the target element up to the root of the document, while Capturing occurs from the root down to the target element.

## 46. What is memoization in JavaScript?

Memoization is an optimization technique in which the results of expensive function calls are cached and returned when the same inputs occur again. It helps improve the performance of functions with repeated calls.

## 47. How does the 'this' keyword behave in arrow functions?

Arrow functions do not have their own 'this' context; instead, they inherit 'this' from the enclosing scope. This behavior is different from regular functions, which have their own 'this' context.

## 48. What is the purpose of the 'finally' block in a try-catch statement?

The 'finally' block contains code that will be executed regardless of whether an exception is thrown or caught. It is often used for cleanup operations, ensuring certain tasks are performed regardless of the outcome of the try and catch blocks.

## 49. How does event delegation work in JavaScript?

Event delegation involves attaching a single event listener to a common ancestor of multiple elements instead of attaching listeners to each individual element. This approach is efficient, especially for large sets of dynamically created elements.

## 50. What is the role of the 'this' keyword in the context of event handlers?

In the context of event handlers, the 'this' keyword refers to the element that triggered the event. It allows for dynamic handling of events on multiple elements using a single event handler function.

---



