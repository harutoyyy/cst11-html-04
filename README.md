# Defining Styles

## Objectives
* create an embedded style
* create class or html tag selectors that can be used to apply a style across a document
* use the position, top, left, width, and height styles to create an html block and place it on the html document

We have looked at Inline Styles, where the style is defined inside an HTML Tag.  A better approach to use an *embedded* style, where the style is included in a style tag.

Open the page1.html document and see how this can be used.

* A tag can include multiple styles. They are separated by a space
* Multiple styles can be defined in the style tag, they are separated by a comma
* A class is defined with a dot (.) followed by the name of the class
* A class definition can be assigned to a specific tag, but can be a global class
* An ID is defined with a hashtag (#) followed by the name of the id
* An ID can be assigned to a specific element, but ID's should be unique

# What is the difference between an ID and a Class?

An ID is intended for unique elements on the page. Think about a button that does a task, like a Save Button.  You only have 1 Save button on a page.
A Class is a reusable style.  Maybe you have a roster for a team, and all of the Tanks need to have one style, and all the Smashers need to have another style.

# Positioning

You can put multiple sections on a page, kind of like using text boxes in Microsoft Word.  We use the position style.  Today we will look at the most basic position: absolute

This creates floating elements in the page, where you set the position in pixels from the top/left of the page, and you set the width and the height.
Look at page2.html for an example.

A page can be imagined as being a coordinate plane, except the (0,0) coordinate is at the top left of the page, but the first number shows the horizontal (x) coordinate and the second shows the vertical (y) coordinate. We can use these coordinates to move blocks of html around the document by using the *position* style along with the *top* and *left* styles.  We can use these styles to create a "text box" or a page within the page.  This block or box can have its own html that is separate from the rest of the page.

How do you put one element/block in front of another if they overlap? Z-index is the style that determines order on a page.  Higher numbers are placed on top of lower numbers!


## Assignment

Style the document called document1.html using embedded Styles.  Use layouts to make the page look better. Work in full screen mode so we don't have to worry about cropping the page. You will need to add all the proper elements to make this a proper html document.
