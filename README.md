# basic-calculator

1. Fork and clone this repo into you booj-coding directory
2. In the `index.html` file, create an html shell.
3. Create a form with two inputs and a submit button. Each of the fields will take a number.
4. Give those inputs unique ids. Give the `form` tag an id as well.
5. Load the jQuery library by either using the url for the jQuery CDN, or by downloading the jQuery library, inserting that library into this directory, and then loading it by using the path to that downloaded library. (Which html tag do you use to load jQuery and JavaScript files? For loading jQuery, should you put the link in the `head` or just above the closing `body` tag? If you download the jQuery file and put it in the `basic-calculator` directory, how do you create the path to it when linking it?)
6. In your `script.js` file, load up jQuery so you can use it here.
7. Create a `submit` event using the form's id.
8. Inside the event, create variables that get the value from each of the inputs.
9. Outside of the event, create a separate function that adds the values and returns the sum.
10. Back inside the event, create a variable that is equal to the function you just created and pass the two values to it.
11. Take that variable you just created and put it in your htmls somewhere (your choice). (There are a couple different methods you can use to accomplish this. One appends the value to another element that is already in the html and the other just sets the html of an existing element.

**Bonus**: This calculator only adds two values. See if you can adjust the calculator to accomplish addition, subtraction, multiplication, and division.
