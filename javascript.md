## JavaScript
***disclaimer*** This resource assumes the reader knows certain principles.
- [  ] Variables
[Variables](#Varibles)
- [  ] Functions, Arrow Functions, Async Fn, 
    callback fn
 [Functions](#Functions)
- [  ] Objects/Arrays
- [  ] Classes
- [  ] Dom Manipulation
- [  ] Error Handling 
- [  ] Promises
- [  ] OOP
- [  ] Design Patterns
- [  ] Libraries and Frameworks

## Variables 

## Functions
---
querySelector() function stores a reference to an element. \

### Question One (Functions): {#Q-Fn1}
Q: What does the code below do?
A: It changes the text area in the element with id headerOne.

```html

<!DOCTYPE HTML>
<html lang="en">
    <body>
        <h1 id="headerOne"></h1>
        <script src="scripts/headerOne.js"></script>
    </body>
    
```

```javascript
// selects stores a reference to element with id #headerOne.
const selected = querySelector("#headerOne")

// modifies text of referenced element.
selected.textContent = "Hello"

```

## Events

addEventListener here listens for user click to run myFn().

```javascript
Example: Runs myFn() when element with id #headerOne is clicked. 

function myFn(){
    console.log("hi")
}

//event listener registers click
document.querySelector("#headerOne").addEventListener("click", myFn())

```

### Assignment One (Events): }{#Q-Events1}
Create an image that changes to different image when clicked.
(HINT: Look at setAttribute function.)

```javascript

function openPokeball() {
test.setAttribute("src","pokemon1.png")
}
const test = document.querySelector("#pokeball-picture")
test.addEventListener("click", test => openPokeball());

```

