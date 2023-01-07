# escape-room

You were at the zoo and accidentally let the animals loose! You're on the run and come across a brick wall with three suspicious doors! Which door will you choose? Where will it lead?!

![Final Product Example](https://github.com/junior-devleague/escape-room/blob/master/assets/example.png)

## Objective

Use **HTML Links, Images, Headers** and correctly specify the file paths to lead us to a new place at each door.

## Prerequisites

To complete this project, students should have the following:
* Basic understanding of HTML structures and attributes.
* Basic understanding of CSS (Selectors, Basic Properties like Width and Height)

## Concepts

HTML | Description
-----|------------
HTML | **H** yper **T** ext **M** arkup **L** anguage used to create the structure of web pages.
element | An element is an individual part, or a building block, of a web page.
attribute | A modifier of an element.
div | A container element.
img | An image element.
a | A link element.
href | An attribute used to specify the link destination.
id | A unique attribute on an element used for targeting in CSS.
class | An attribute that can be applied to multiple elements used for targeting in CSS.

File Paths | Description
---------- | -----------
File Path | Describes the location of a file in a web site's folder structure.
Absolute File Path | Full URL to an Internet file. Ex. https://www.w3schools.com/images/picture.jpg
Relative File Path | Path to a file relative to the current page. Ex. assets/example.png

Relative File Paths | Description
------------------- | -----------
images/picture.jpg | Goes into the images folder, then points to the picture.jpg.
../images/picture.jpg | Goes outside of the current folder, then goes into the images folder, then points to the picture.jpg.

## Your Challenge

### Part I

To complete Part I, fulfill the following requirements:
1. Set up your project file structure through the command line.
2. Create the following:
* HTML file
* CSS folder with a CSS file
* Folder called "rooms"  
3. Link all of your files correctly.

Make sure you have the assets from the repository as well.

### Part II Main HTML

To complete Part II, fulfill the following requirements:

1. Create a ```div``` with an ```id``` of "container".
  * **Inside** of this div, create the following:
    * A link element *Do you remember the tag name for a link element? Look at the table above!* **Inside** of this link element, create an image element with ```id``` of "door1" and ```class``` of "door".
    *  A link element. **Inside** of this link element, create an image element with ```id``` of "door2" and ```class``` of "door".
    * A link element. **Inside** of this link element, create an image element with ```id``` of "door3" and ```class``` of "door".

    **Specify the right ```src``` for the image. Find the door image in the assets folder. Create the path to specify the door image and place that in the img src!**

2. Inside of the rooms folder, create 3 HTML files as follows:
* dungeon.html
* outer-space.html
* the-future.html

3. Now go back to the index.html file. When we click on one of the doors we want to be linked to another HTML file! How do we do that? We need to use a relative file path to specify the location of our HTML file! How do we go from where we currently are in the index.html to the dungeon, outer-space, and the-future HTML files?
  * In the ```href``` attribute of the 1st link element, specify the path to the dungeon.html file.
  * In the ```href``` attribute of the 2nd link element, specify the path to the outer-space.html file.
  * In the ```href``` attribute of the 3rd link element, specify the path to the the-future.html file.

### Part III Main CSS

1. Target the ```id``` of "container".
  * Set the ```width``` to ```calc(100vw)```. This will get the full width of the page.
  * Set the ```height``` to ```calc(100vh)```. This will get the full height of the page.
  * Set the background-image to the brick wall image. *Hint: https://www.w3schools.com/cssref/pr_background-image.asp Remember, we want the brick wall image. How do we specify the path of that?*
2. Target the ```class``` of "door".
  * Set the ```width``` to ```200px```.
  * Set the ```height``` to ```400px```.
3. Target the ```id``` of "door1".
  * Set the ```position``` to ```fixed```. This allows us to specify exactly where we want the image to stay on the page.
  * Place the door at the very bottom of the page and some pixels away from the left side of the page. Make sure the doors do not overlap. Use the properties ```bottom```, ```left```, ```top```, and/or ```right``` and see which works best. Test out different values! *Hint: https://www.w3schools.com/cssref/pr_class_position.asp*

  **Do this for all 3 doors!**

### Part IV Multiple CSS Files

To complete Part IV, fulfill the following requirements:

1. Go into your **CSS Folder**.
2. Create 3 CSS files as follows:
  * dungeon.css
  * outer-space.css
  * the-future.css

### Part V The Dungeon HTML

To complete Part V, fulfill the following requirements:

1. Go into your dungeon.html file.
2. Link the corresponding dungeon.css file. *Hint: How do you go from dungeon.html to dungeon.css?*
3. In this HTML file, create a ```div``` with an ```id``` of "container".
  * **Inside** of this div, create an ```h1``` with an ```id``` of "text". Inside of this ```h1```, type "BEWARE OF THE DRAGON".
  * Create a link element with an ```id``` of "home". In the ```href``` attribute, specify the location of the index.html file. *Hint: How do you go from dungeon.html to index.html?*

### Part VI Dungeon CSS

To complete Part VI, fulfill the following requirements:

1. Go into your dungeon.css file.
2. Target the ```id``` of "container".
  * Set the ```width``` to ```calc(100vw)```. This will specify the full width of the page.
  * Set the ```height``` to ```calc(100vh)```. This will specify the full height of the page.
  * Set the background-image to the dragon.gif. *Remember how you set the background image in the earlier part?*
3. Target the ```id``` of "text".
  * Set the background color to white! How do you do that? *https://www.w3schools.com/cssref/pr_background-color.asp*
4. Target the ```id``` of "home".
  * Set the background color to white!

### Part VII Outer Space HTML

To complete Part VII, fulfill the following requirements:

1. Go into your outer-space.html file.
2. Link the corresponding outer-space.css file. *Hint: How do you go from outer-space.html to outer-space.css?*
3. In this HTML file, create a ```div``` with an ```id``` of "container".
  * **Inside** of this div, create an ```h1``` with an ```id``` of "text". Inside of this ```h1```, type "THE ALIENS ARE COMING".
  * Create a link element with an ```id``` of "home". In the ```href``` attribute, specify the location of the index.html file. *Hint: How do you go from outer-space.html to index.html?*

### Part VIII Outer Space CSS

To complete Part VIII, fulfill the following requirements:

1. Go into your outer-space.css file.
2. Target the ```id``` of "container".
  * Set the ```width``` to ```calc(100vw)```. This will specify the full width of the page.
  * Set the ```height``` to ```calc(100vh)```. This will specify the full height of the page.
  * Set the background-image to the alien.gif. *Remember how you set the background image in the earlier part?*
3. Target the ```id``` of "text".
  * Set the background color to white! How do you do that? *https://www.w3schools.com/cssref/pr_background-color.asp*
4. Target the ```id``` of "home".
  * Set the background color to white!

### Part IX The Future HTML

To complete Part IX, fulfill the following requirements:

1. Go into your the-future.html file.
2. Link the corresponding the-future.css file. *Hint: How do you go from the-future.html to the-future.css?*
3. In this HTML file, create a ```div``` with an ```id``` of "container".
  * **Inside** of this div, create an ```h1``` with an ```id``` of "text". Inside of this ```h1```, type "THIS IS THE FUTURE!!".
  * Create a link element with an ```id``` of "home". In the ```href``` attribute, specify the location of the index.html file. *Hint: How do you go from the-future.html to index.html?*

### Part X The Future CSS

To complete Part X, fulfill the following requirements:

1. Go into your the-future.css file.
2. Target the ```id``` of "container".
  * Set the ```width``` to ```calc(100vw)```. This will specify the full width of the page.
  * Set the ```height``` to ```calc(100vh)```. This will specify the full height of the page.
  * Set the background-image to future.gif. *Remember how you set the background image in the earlier part?*
3. Target the ```id``` of "text".
  * Set the background color to white! How do you do that? *https://www.w3schools.com/cssref/pr_background-color.asp*
4. Target the ```id``` of "home".
  * Set the background color to white!

Awesome Job! Check if it works and takes you to these places when you click on the doors!

### Stretch Goals

1. Create another door in the index.html file that will take you to a place of your choosing!
2. In this new place, create ANOTHER door that will take you to ANOTHER new place!
