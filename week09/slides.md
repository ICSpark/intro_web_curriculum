# Day 9

## Objective
- Handling Events

## Table of Contents
1. **Review Game**
2. **Review Project**
3. **Lecture and Activities**
  * Events
  * Mouse Events
  * Keyboard Events 
  * Handling Events with onevent and addListenerEvent
4. **Live code & Exercise**
5. **Project in Breakout Sessions with Mentors**

## Lecture and Activities

### EVENTS
* Actions that happen on webpages 
* Examples:
  * User clicks
  * Web page loaded
  * Mouse moves over an element
  * Input field is changed
  * User presses a key on the keyboard 


### REACTING TO EVENTS
* We can react to events in different ways
  * Assign events using HTML DOM (1)
  * Add an EventListener (2)
  * Assign HTML event attributes (3)
```javascript
var button = document.getElementById("button");

button.onclick = function () {                    // 1)
  button.innerHTML = "Changed!"; 
};

button.addEventListener("click", function(){       // 2)
  button.innerHTML = "Changed!";
});
// ----------------------------------------------
<button onclick="changeText()">Click me!</button>  // 3)
```

### MOUSE EVENTS using onevent handlers
* onclick - the event occurs when the user clicks on an element
* oncontextmenu - the event occurs when the user right-clicks on an element to open a context menu
*  etc.

### Using Mouse Properties & Methods
* Event handler functions are passed an argument: the event object 
* The event object holds information about that specific event 
* We can then use the properties of the event using dot notation 
* Functions can be set as event handlers. When you interact with an element and cause an event, the function will execute. 
* Notice the difference between onclick and click. You can find a full list of events here!


```javascript
window.addEventListener("mousemove", function(event){
  console.log(event.clientX);
});
```

```javascript
window.addEventListener("keydown", function(event){
  // If right arrow is pressed...
  if (event.keyCode === 39) {
    left = left + 10;
    character.style.left = left + "px";
  } else {
    console.log("Press the right arrow key!");
  }
});
```

### Handling Events with addEventListener
1. The source. Most sources of an event will be document elements (a button, paragraph, div, header, etc.) Sources can also be the window (the browser window)
2. The event is attached to a source (click, load, mouseover, keypress, etc.)
3. The response happens because of the event. Output or other document elements are changed in the response behavior.

```Javascript
var btn = document.getElementById("my-button");

btn.addEventListener("click", responseFunction);

function responseFunction() {
  console.log("Hi there!");
}
```

1. The source: document.getElementById(“my-button”);
2. The event: click
3. The response: function responseFunction()
4. The response behavior: console.log(“Hi there!”);

### 
* Do not include # in ID string for getElementById
* “klick” is not a valid event type for JavaScript
* Function handlers names need to match to a declared function. goof is not declared, but goofy is.

```Javascript
var btn = document.getElementById("my-button");

btn.addEventListener("click", goofy);

function goofy() {
  alert("Yay it works!");
}
```
 
## Project in Breakout Sessions with Mentors
* Create HTML Elements
* Use Flexbox to position elements
* Use Javascript to handle events and manage DOM
* Go to: [Fishtank](https://github.com/junior-devleague/fishtank)
