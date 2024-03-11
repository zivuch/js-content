# Suggested Content

### Day 1: Introduction to JavaScript Basics

- Introduction to JavaScript
- JavaScript Fundamentals
  - Hello, world!
  - Code structure
  - The modern mode, "use strict"  $\color{red}{**_ new _**}$ 
    - In JavaScript, "use strict"; is a directive that tells the browser to execute the code in strict mode. When you use strict mode, JavaScript enforces stricter rules and generates more errors in certain situations. This can help you write cleaner, more robust code and catch potential issues early.
  - Variables
  - Data types
  - Interaction: alert, prompt, confirm
  - Basic operators, maths
  - Comparisons
  - Conditional branching: if, '?' 
  - Logical operators
  - Nullish coalescing operator '??' **_ new _**
    - The Nullish coalescing operator ?? is a feature in JavaScript that provides a concise and readable way to handle default values for variables that might be null or undefined.
  - Loops: while and for
  - The "switch" statement
  - Functions
  - Function expressions

**_ Self learning: _**

- The old "var"
- Code Quality *
  - Debugging in the browser 
  - Coding Style **_ new _**
    - That is actually the art of programming – to take a complex task and code it in a way that is both correct and human-readable. A good code style greatly assists in that.
  - Comments 

### Day 2: Intermediate JavaScript Concepts

- Objects: The Basics
  - Objects
  - Object references and copying
  - Object methods, "this", Global object
  - Constructor, operator "new" 
  - Optional chaining '?.' **_ new _**
    - The optional chaining ?. is a safe way to access nested object properties, even if an intermediate property doesn’t exist.
- Data Types
  - Methods of primitives
  - Arrays
  - Array methods
- Object.keys, values, entries
- Array.map, filter, reduce, find, findIndex
- Destructuring assignment
- JSON methods, toJSON

**_ Self learning: _**

- Advanced Array Methods
- Advanced Object Methods
- Garbage collection **_ new _**
   - JavaScript garbage collection is an automatic memory management process that helps free up memory used by objects that are no longer needed or referenced in a JavaScript program.
- Symbol type **_ new _**
  - In JavaScript, the Symbol type is a unique and immutable data type introduced in ECMAScript 2015 (ES6). Symbols are used to create unique identifiers that can be used as property keys for object propertie
- Object to primitive conversion **_ new _**
  - JavaScript automatically converts objects to primitive values when they are used in contexts where primitives are expected. This process is called "object-to-primitive conversion."

### Day 3: DOM Manipulation

- DOM Basics
  - Browser environment, specs
  - DOM tree
  - Walking the DOM
  - Searching: getElement*, querySelector*
  - Node properties: type, tag and contents
  - Attributes and properties
  - Modifying the document
  - Styles and classes
- Events Introduction
  - Introduction to browser events
  - Bubbling and capturing
  - Event delegation **_ new _**
    - Capturing and bubbling allow us to implement one of the most powerful event handling patterns called event delegation.
  - Browser default actions **_ new _**
     - Many events automatically lead to certain actions performed by the browser. For instance: A click on a link – initiates navigation to its URL. A click on a form submit button – initiates its submission to the server. Pressing a mouse button over a text and moving it – selects the text.

**_ Self learning: _**

- Dispatching custom events **_ new _**
  - Dispatching custom events in JavaScript allows you to create and dispatch your own custom events, which other parts of your code can listen for and react to. This provides a way to implement custom communication between different parts of your application.
- Element size and scrolling **_ new _**
  - There are many JavaScript properties that allow us to read information about element width, height and other geometry features.
- Window sizes and scrolling **_ new _**
   - In JavaScript, you can access information about the window size and scrolling position of a web page using properties and methods provided by the window object.
- Date and time

### Day 4: Working with Forms and UI Events

- UI Events
  - Mouse events
  - Pointer events
  - Keyboard events
  - Scrolling
- Mutation observer **_ new _**
  - MutationObserver is a built-in object that observes a DOM element and fires a callback when it detects a change.
- Form Properties and Methods
  - Form properties and methods
  - Forms: event and method submit

**_ Self learning: _**

- HTTP Methods

### Day 5: Advanced JavaScript Concepts

- Map and Set **_ new _**
- Advanced Working with Functions
  - Function expressions
  - Arrow functions
  - Rest parameters and spread syntax
  - The "new Function" syntax **_ new _**
    - Map and Set are useful data structures in JavaScript for storing collections of key-value pairs and unique values, respectively. They provide efficient methods for adding, removing, and iterating over data, making them versatile tools for various programming tasks.
- Variable scope, closure, Currying
- Scheduling: setTimeout and setInterval

**_ Self learning: _**

- WeakMap and WeakSet **_ new _**
  - WeakMap and WeakSet provide mechanisms for associating data with objects and tracking object existence in a way that allows for garbage collection when objects are no longer needed. 
- Recursion and stack **_ new _**
  - Recursion is a programming pattern that is useful in situations when a task can be naturally split into several tasks of the same kind, but simpler
- Function binding **_ new _**
  - Function binding in JavaScript involves explicitly setting the value of this within a function. This is particularly useful in situations where you want to ensure that a function is called with a specific this value, regardless of how it's invoked.
- Decorators and forwarding, call/apply **_ new _**
  - JavaScript gives exceptional flexibility when dealing with functions. They can be passed around, used as objects, and now we’ll see how to forward calls between them and decorate them.
- Function object, NFE **_ new _**
  - In JavaScript, functions are first-class objects, which means they can be treated like any other object. This allows functions to be passed as arguments to other functions, returned from functions, and assigned to variables.

### Day 6: Error Handling and Promises

- Error Handling
  - Error handling, "try...catch"
  - Custom errors, extending Error
- Synchronous & Asynchronous programming
- Promises
  - Introduction: callbacks
  - Promise basics
  - Promises chaining
  - Promise methos: all, allSettled, race, any, resolve/reject
  - Error handling with promises

  **_ Self learning: _**

  - Microtasks

### Day 7: Asynchronous JavaScript Fetch API and Advanced FORM Manipulation

- Async/Await
- Fetch API
- Advanced FORM Manipulation
  - Form manipulation
  - Form validation

### Day 8: Wrap-up and Practical Application **_ new _**

- Review concepts covered throughout the course
- Work on a small project or exercises to apply the learned concepts
- Q&A session and addressing any remaining doubts or questions
