## JavaScript

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

querySelector() function stores a reference to an element.
Example: Uses querySelector() to change text of h1 element.

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
Example: Run myFn() when element with id  #headerOne is clicked. 

```javascript
function myFn(){
    console.log("hi")
}

//event listener registers click
document.querySelector("#headerOne").addEventListener("click", myFn())

```

