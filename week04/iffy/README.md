# iffy

Let's create a shape teller so you'll never have to be iffy about shapes ever again! Is it a triangle, a quadrilateral, or something else? Users can input the number of sides for the shape they're thinking about. Upon clicking a button, the mysterious shape will be revealed!

![Devball](https://github.com/junior-devleague/iffy/blob/master/iffy.gif)

## Objective
Use **JavaScript If Statements** to change the **innerHTML** of a text area and display the name of shapes with different numbers of sides.

## Prerequisites
To complete this project, students should have the following:
* Basic understanding of HTML structure and attributes.
* Basic understanding of JavaScript and DOM.

## Your Challenge

### Part I: Create your HTML Page
To complete this warmup, fulfill the following requirements:
1. Set up your project file structure through the command line.
2. Create the following:
* HTML, CSS, JS file
3. Link all of your files correctly.
4. Create the following:
* ```h1``` element for a greeting.
* ```p``` element that says "Return the shape with this many sides:"
* ```input``` element with an id to take in user input.
* ```button``` element with an id to click and return the solution.
* ```p``` element with an id to store the solution.

Make sure your HTML structure is neat! Go through the list at https://www.w3schools.com/html/html5_syntax.asp. and see if every tip is followed. Show an instructor before proceeding to Part II.

### Part II: Adding JS
To complete the second part of this warmup, fulfill the following requirements:
1. In your JS file, you will need to store the ```input```, ```button```, and 2nd ```p``` element in variables.
2. Add an ```Event Listener``` to the ```button``` that will listen for a ```click```.
3. Create if statements in the function for this event listener.
* If the value in the input box is 3, the ```innerHTML``` of the 2nd p tag should display the string saying the correct shape with 3 sides. (e.g. "Triangle")
* If the value in the input box is 4, the ```innerHTML``` of the 2nd p tag should display the string saying the correct shape with 4 sides.
* If the value in the input box is 5, the ```innerHTML``` of the 2nd p tag should display the string saying the correct shape with 5 sides.
* If the value in the input box is 6, the ```innerHTML``` of the 2nd p tag should display the string saying the correct shape with 6 sides.
* If the value in the input box is 7, the ```innerHTML``` of the 2nd p tag should display the string saying the correct shape with 7 sides.
* If the value in the input box is 8, the ```innerHTML``` of the 2nd p tag should display the string saying the correct shape with 8 sides.
* If the value in the input box is 9, the ```innerHTML``` of the 2nd p tag should display the string saying the correct shape with 9 sides.
* If the value in the input box is 10, the ```innerHTML``` of the 2nd p tag should display the string saying the correct shape with 10 sides.  
* If the value is NONE of these values, the ```innerHTML``` of the 2nd p tag should display the string "Try Again!".

### Resources
https://www.w3schools.com/tags/tag_input.asp
https://www.w3schools.com/jsreF/met_element_addeventlistener.asp
https://www.w3schools.com/jsref/met_document_getelementbyid.asp

### Stretch Goals
1. Pretty up your page!!
2. Add the image of the corresponding shape to the page. Hint: Change the ```image.src```!
