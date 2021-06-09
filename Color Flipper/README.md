# Hi guys!


## This is a project in **Javascript** to demonstrate _background color_ change

# *ColorFlipper*

- It has two pages, which have similar functionality using two different approaches
- The _index.html_ is similar to _hex.html_
- In the *app.js* file, the colors are hard coded and triggers the event listener encoded in the button button
- In the *hex.js* file there is an array and a function to generate random numbers 


### Key concepts covered :

- **arrays  :** 
    An array is a special variable, which can hold more than one value at a time
    It is declared as: 
    ```javascript
    var array_name = [item1, item2, ...];
    ```

- **document.getElementById() :** The getElementById() method returns the element that has the ID attribute with the specified value

- **document.querySelector() :** The querySelector() method returns the first element that matches a specified CSS selector(s) in the document. _Note:_ The querySelector() method only returns the first element that matches the specified selectors. To return all the matches, use the querySelectorAll() method instead.
If the selector matches an ID in document that is used several times (Note that an "id" should be unique within a page and should not be used more than once), it returns the first matching element


- **addEventListener() :** The document.addEventListener() method attaches an event handler to the document

- **document.body.style.backgroundColor :** The backgroundColor property sets or returns the background color of an element

- **Math.floor() :** The floor() method rounds a number DOWNWARDS to the nearest integer, and returns the result. If the passed argument is an integer, the value will not be rounded


- **Math.random() :** This JavaScript function always returns a random number between min (included) and max (excluded)

- **array.length() :** The length property sets or returns the number of elements in an array.

## **The Logic**

**_app.js_**

- In this file, first I have taken an array of colors.
- The size of array colors is 4. I have taken three ways to define that color, in three formats of defining color in JS.
    ```javascript
    const colors = ["green", "red", "rgba(133,122,200)", "#f15025"];
    ```
- The next next step is to capture the id given to button in a variable.
- Used query selector to navigate the background color class of the css selector
- By adding an event listener to the button and assigning a function to change the background color using randomColor method.

**_hex.js_**

- It is quite similar to the app.js file
- instead of using an array of colors the values which combine to make a hex value is stored in an array.
- instead of assigning colors stored in array, I have created the hex valued colorsusing loops and random numbers





![ColorFlipper](https://www.vanillajavascriptprojects.com/static/9fe099223fed3b9c2b37a545f8ea106a/af144/Screen_Shot_2020-04-13_at_8.57.42_PM.png)






