The following content is the compilation of the entire UDACITY SCHOLARSHIP PRE-SELECTION FACE learning notes that I decided to keep as a reminder... I hope you can make good use of this information... (By Julie Hutchinson 01/2018)

>* Trees represent data that makeup websites: A parent branch `<ul>` has many children `<li></li>`.

>* DOCTYPE: Describes the type of HTML. `<!DOCTYPE html>` helps the browser determine what type of HTML document it’s trying to parse and display.

>* Browsers look for this doctype declaration to determine which rendering mode to use to render the site. Generally, newer sites follow standard HTML specifications. The current standard HTML specification is called HTML5.

>* `<head>` Describes meta information about the site, such as the title, and provides links to scripts and stylesheets the site needs to render and behave correctly.

>* `<body>` Describes the actual content of the site that users will see.

>* To open the web development tools on a Mac: Command + Option + i

>* apply `<style>` tag to apply css to a page.

>* apply `<script type="text/javascript">` tag to apply javascript to a page.
>* CSS measurement units can be: _absolute-_ (100px/in/cm/mm) fixed units of measurement. _relative-_ (100%/em/vw -viewport width-/vh -viewport height-) units that are a comparison to another linked property.

## HTML5 Semantic Elements

>- `<header>` - Defines a header for a document or a section
>- `<nav>` - Defines a container for navigation links
>- `<section>` - Defines a section in a document
>- `<article>` - Defines an independent self-contained article
>- `<aside>` - Defines content aside from the content (like a sidebar)
>- `<footer>` - Defines a footer for a document or a section
>- `<details>` - Defines additional details
>- `<summary>` - Defines a heading for the `<details>` element

1. The outermost sectioning element is always the <body></body> tag.

2. Sections in HTML5 can be nested.

3. Each section has its own heading hierarchy. Each of them (even the innermost nested section) can have an h1 tag.

4. While the document outline is primarily defined by the 5 sectioning elements, it also needs proper headings for each section.

5. It’s always the first heading element (let it be h1 or a lower rank heading tag) that defines the heading of the given section. The following heading tags inside the same section need to be relative to this. (If the first heading is an h3 inside a sectioning element, don’t put an h3 after that.)

6. The sections defined by the <nav></nav>, and the <aside></aside> tags don’t belong to the main outline of the HTML document, they are usually not rendered initially by assistive technologies.

7. Each section (body, section, article, aside, nav) can have their own <header></header> and <footer></footer> tags, that defines the header (such as logo, author’s name, dates, meta info, etc.) and the footer (copyright, notes, links, etc.) of that section.

---
  1. What CSS property is used to __italicize__ text? font-style
  2. What CSS property is used to __underline__ text? text-decoration
  3. What CSS property is used to __uppercase__ text? text-transform
  4. What CSS property is used to __bold__ text? font-weight

  5. Which HTML elements match the given CSS statement?

```
  .right {
       text-align: right;
  }

<div class="right"></div>
<p class="highlight module right"></p>
```

6. The `font-family` property is used to _change the font_ to Helvetica, Arial, or the default sans-serif font installed on the operating system.

7. The `font-size` property is used to increase the _size of the font_ to be larger

8. The `text-transform` and `text-decoration` properties are used to _capitalize_ and _underline_ the text.

9. Color is used to change the color.
10. Every CSS statement is made up of a selector and a declaration block. The __selector__ tells the browser what HTML element we want to style and the __declaration block__ tells the browser what styles need to be applied to that HTML.

---
>- A stylesheet is a file containing the code that describes how elements on your webpage should be displayed.

>- To link your stylesheet to your html file, you'll need to create a `<link>` to your stylesheet in your HTML.

```
<link href="path-to-stylesheet/stylesheet.css" rel="stylesheet">
```

>- The href attribute specifies the path to the linked resource and the rel attribute names the relationship between the resource and your document.

```
<head>
  <title>My Webpage</title>
  <!-- ... -->
  <link href="path-to-stylesheet/stylesheet.css" rel="stylesheet">
  <!-- ... -->
</head>
```

## Sublime and Atom Keyboard shortcuts

<table>
    <tr>
        <td>Mac</td>
        <td>Windows/Linux</td>
    </tr>
    <tr>
        <td>
          <ul>
            <li>Undo: command + Z</li>
            <li>Redo: command + shift + Z</li>
            <li>Redo: command + Y</li>
            <li>Delete line: Ctrl + shift + K</li>
            <li>Delete line (from any location within that line): command + X</li>
          </ul>
        </td>
        <td>
          <ul>
            <li>Undo: Ctrl + Z</li>
            <li>Redo: Ctrl + shift + Z</li>
            <li>Redo: Ctrl + Y</li>
            <li>Delete line: Ctrl + shift + K</li>
            <li>Delete line (from any location within that line): Ctrl + X</li>
          </ul>
        </td>
    </tr>
    <tr>
        <td>
          <ul>
            <li>Move Line Up: Ctrl + command + up</li>
            <li>Move Line Down: Ctrl + command + down</li>
            <li>Go to line #: Ctrl + G</li>
          </ul>
        </td>
        <td>
          <ul>
            <li>Move Line Up: Ctrl + up</li>
            <li>Move Line Down: Ctrl + down</li>
            <li>Go to line #: Ctrl + G</li>
          </ul>
        </td>
    </tr>
    <tr>
        <td>Duplicate (w/w.o selection): command + shift + D</td>
        <td>Duplicate (w/w.o selection): Ctrl + shift + D</td>
    </tr>
    <tr>
        <td>
          <ul>
            <li>Select Word: command + D</li>
            <li>Select Line: command + L</li>
            <li>Select All: command + A</li>
            <li>Select Every Instance: command + control + G</li>
          </ul>
        </td>
        <td>
          <ul>
            <li>Select Word: Ctrl + D</li>
            <li>Select Line: Ctrl + L</li>
            <li>Select All: Ctrl + A</li>
            <li>Select Every Instance: Alt + F3</li>
          </ul>
        </td>
    </tr>
    <tr>
        <td>
          <ul>
            <li>Move Cursor to previous word: option + left_arrow</li>
            <li>Move Cursor to next word: option + right_arrow</li>
            <li>Move Cursor to start of line: command + left_arrow</li>
            <li>Move Cursor to end of line: command + right_arrow</li>
            <li>Move Cursor to start of document: command + upward_arrow</li>
            <li>Move Cursor to end of document: command + downward_arrow</li>
          </ul>
        </td>
        <td>
          <ul>
            <li>Move Cursor to previous word: Ctrl + left_arrow</li>
            <li>Move Cursor to next word: Ctrl + right_arrow</li>
            <li>Move Cursor to start of line: Home</li>
            <li>Move Cursor to end of line: End</li>
            <li>Move Cursor to start of document: Ctrl + Home</li>
            <li>Move Cursor to end of document: Ctrl + End</li>
          </ul>
        </td>
    </tr>
    <tr>
        <td>
          <ul>
            <li>Jump to open/close ()[]{}: command + M</li>
            <li>Jump to definition: command + R</li>
          </ul>
        </td>
        <td>
          <ul>
            <li>Jump to open/close ()[]{}: Ctrl + M</li>
            <li>Jump to Definition: Ctrl + R</li>
          </ul>
        </td>
    </tr>
    <tr>
      <td>
        <ul>
          <li>Cut: command + X</li>
          <li>Copy: command + C</li>
          <li>Paste: command + V</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>Cut: Ctrl + X</li>
          <li>Copy: Ctrl + C</li>
          <li>Paste: Ctrl + V</li>
        </ul>
      </td>
    </tr>
    <tr>
        <td>
          <ul>
            <li>Indent: command + ]</li>
            <li>Unindent: command + [</li>
          </ul>
        </td>
        <td>
          <ul>
            <li>Indent: Ctrl + ]</li>
            <li>Unindent: Ctrl + [</li>
          </ul>
        </td>
    </tr>
    <tr>
        <td>
          <ul>
            <li>Toggle comment: command + /</li>
          </ul>
        </td>
        <td>
          <ul>
            <li>Toggle comment: Ctrl + /</li>
          </ul>
        </td>
    </tr>
    <tr>
        <td>
          <ul>
            <li>New Tab: command + N</li>
            <li>Switch Tab Left: command + shift + [</li>
            <li>Switch Tab Right: command + shift + ]</li>
            <li>Close Tab: command + W</li>
            <li>Reopen Tab: command + shift + T</li>
          </ul>
        </td>
        <td>
          <ul>
            <li>New Tab: Ctrl + N</li>
            <li>Switch Tab Left: Ctrl + PgUp</li>
            <li>Switch Tab Right: Ctrl + PgDn</li>
            <li>Close Tab: Ctrl + W</li>
            <li>Reopen Tab: Ctrl + shift + T</li>
          </ul>
        </td>
    </tr>
    <tr>
        <td>
          <ul>
            <li>Quick Open: command + P</li>
          </ul>
        </td>
        <td>
          <ul>
            <li>Quick Open: Ctrl + P</li>
          </ul>
        </td>
    </tr>
    <tr>
        <td>
          <ul>
            <li>Find: command + F</li>
          </ul>
        </td>
        <td>
          <ul>
            <li>Find: Ctrl + F</li>
          </ul>
        </td>
    </tr>
</table>

## Conditionals

### Logical Operators

<table>
    <tr>
        <td>Operator</td>
        <td>Meaning</td>
        <td>Example</td>
        <td>How it works</td>
    </tr>
    <tr>
        <td> && </td>
        <td>Logical AND</td>
        <td>condition1 && condition2</td>
        <td>Returns true if both condition1 and condition2 evaluate to true</td>
    </tr>
    <tr>
        <td> || </td>
        <td>Logical OR</td>
        <td>condition1 || condition2</td>
        <td>Returns true if either condition1 or condition2 (or even both) evaluates to true</td>
    </tr>
    <tr>
        <td> ! </td>
        <td>Logical NOT</td>
        <td>!condition1</td>
        <td>Returns the opposite of condition1. If condition1 is true, then !condition1 is false</td>
    </tr>
</table>

### Truthy and Falsy

>- A value is falsy if it converts to false when evaluated in a boolean context. For example, an empty String "" is falsy because, "" evaluates to false.

```
if ("") {
    console.log("the value is truthy");
} else {
    console.log("the value is falsy");
}

>>> the value is falsy
```

>- The list of all of __falsy__ values is:
>>- false (the Boolean expression) === false
>>- null (the type) === false
>>- 0 (the number) === false
>>- 0.0 (the number) === false
>>- "" (the empty string) === false
>>- NaN (the odd value) === false

>- A value is truthy if it converts to true when evaluated in a boolean context. For example, the number 1 is truthy because, 1 evaluates to true.

```
if (1) {
    console.log("the value is truthy");
} else {
    console.log("the value is falsy");
}

>>> the value is truthy
```

>- The list of some of __truthy__ values is:
>>- true (the Boolean expression) === true
>>- 42 (the number) === true
>>- "0" (the string) === true
>>- "null" (the null string) === true
>>- "undefined" (the string) === true
>>- [] (the expression) === true
>>- {} (the expression) === true

### Ternary Operator

>- The ternary operator provides you with a shortcut alternative for writing lengthy if...else statements.

```
conditional ? (if condition is true) : (if condition is false)
```

> To use the ternary operator,

>>- first provide a conditional statement on the left-side of the ?.
>>- Then, between the ? and : write the code that would run if the condition is true
>>- and on the right-hand side of the : write the code that would run if the condition is false.

For example:

```
let isGoing = true;
let color = isGoing ? "green" : "red";
console.log(color);

>>> green
```

### Switch statement
>- A switch statement is an another way to chain multiple else if statements that are based on the same value without using conditional statements. Instead, you just switch which piece of code is executed based on a value.

```
switch (option) {
  case 1:
    console.log("You selected option 1.");
  case 2:
    console.log("You selected option 2.");
  case 3:
    console.log("You selected option 3.");
  case 4:
    console.log("You selected option 4.");
  case 5:
    console.log("You selected option 5.");
  case 6:
    console.log("You selected option 6.");
}
```

>- Here, each else if statement (option === [value]) has been replaced with a case clause (case: [value]) and those clauses have been wrapped inside the switch statement.

>- When the switch statement first evaluates, it looks for the first case clause whose expression evaluates to the same value as the result of the expression passed to the switch statement. Then, it transfers control to that case clause, executing the associated statements. So, if you set option equal to 3...

```
let option = 3;

switch (option) {
  ...
}

>>> You selected option 3.
>>> You selected option 4.
>>> You selected option 5.
>>> You selected option 6.
```

>- ...then the switch statement prints out options 3, 4, 5, and 6.

### Break statement
>- The break statement can be used to terminate a switch statement and transfer control to the code following the terminated statement. By adding a break to each case clause, you fix the issue of the switch statement falling-through to other case clauses.

```
let option = 3;

switch (option) {
  case 1:
    console.log("You selected option 1.");
    break;
  case 2:
    console.log("You selected option 2.");
    break;
  case 3:
    console.log("You selected option 3.");
    break;
  case 4:
    console.log("You selected option 4.");
    break;
  case 5:
    console.log("You selected option 5.");
    break;
  case 6:
    console.log("You selected option 6.");
    break; // technically, not needed
  }
```
## Parts of a While Loop

>- When to start: The code that sets up the loop — defining the starting value of a variable for instance.
>- When to stop: The logical condition to test whether the loop should continue.
>- How to get to the next item: The incrementing or decrementing step — for example, x = x * 3 or x = x - 1

```
let start = 0; // when to start
while (start < 10) { // when to stop
  console.log(start);
  start = start + 2; // how to get to the next item
}

>>> 0 2 4 6 8
```

## Functions

>- Functions package up code so you can easily use (and reuse) a block of code. Parameters are variables that are used to store the data that's passed into a function for the function to use. Arguments are the actual data that's passed into a function when it is invoked:

```
// x and y are parameters in this function declaration

function add(x, y) {
  // function body
  let sum = x + y;
  return sum; // return statement
}

// 1 and 2 are passed into the function as arguments
let sum = add(1, 2);
```

>- The function body is enclosed inside curly brackets:

```
function add(x, y) {
  // function body!
}
```

>- Return statements explicitly make your function return a value:

```
>>> sum;
```

>- You invoke or call a function to have it do something:

```
add(1, 2);

>>> 3
```

### variables

>- If an identifier is declared in global scope, it's available everywhere.
>- If an identifier is declared in function scope, it's available in the function it was declared in (even in functions declared inside the function).
>- When trying to access an identifier, the JavaScript Engine will first look in the current function. If it doesn't find anything, it will continue to the next outer function to see if it can find the identifier there. It will keep doing this until it reaches the global scope.
>- Global identifiers are a bad idea. They can lead to bad variable names, conflicting variable names, and messy code.

### Shadowing

```
let x = 1;

function addTwo() {
  x = x + 2;
}

addTwo();
x = x + 1;
console.log(x);

>>> 4

```

versus

```
let x = 1;

function addTwo() {
  let x = x + 2;
}

addTwo();
x = x + 1;
console.log(x);

>>> 2

```

### Hoisting

>- Before any JavaScript gets executed, all function declarations are "hoisted" to the top of their current scope.

```
findAverage(5,9);

function findAverage(x, y) {
  let answer = (x + y)/2;
  return answer;
}
```
>- What value will be printed to the console?

```
sayHi("Julia");

function sayHi(name) {
  console.log(greeting + " " + name);
  let greeting;
}

>>> undefined Julia

```

### Function Declarations

>- In JavaScript, when a function is stored inside a variable it's called a __function expression__.

```
let catSays = function(max) {
  let catMessage = "";
  for (let i = 0; i < max; i++) {
    catMessage += "meow ";
  }
  return catMessage;
};
```

>- The following is an __anonymous function__, a function with no name that is stored in a variable called catSays.

```
let catSays = function(max) {
  // code here
};

catSays;

>>> {
  function(max) {
    let catMessage = ""
    for (let i = 0; i < max; i++) {
      catMessage += "meow ";
    }
    return catMessage;
  }
}

```

### Function expressions and hoisting

>- All function declarations are hoisted and loaded before the script is actually run. Function expressions are not hoisted, since they involve variable assignment, and only variable declarations are hoisted. The function expression will not be loaded until the interpreter reaches it in the script.

```
function cat() {
  function purr() {
    return "purrrr!";
  }
  console.log(meow());

  let meow = function(max) {
    for(let i = 0 ; i < max ; i++) {
      catMessage += "meow ";
    }
    return catMessage;
  }

}

>>> Uncaught TypeError: meow is not a function(...)
```

versus

```
console.log(cat());

function cat() {
  function purr() {
    return "purrrr!";
  }

  let meow = function(max) {
    for(let i = 0 ; i < max ; i++) {
      catMessage += "meow ";
    }
    return catMessage;
  }

}

>>> purrrr!
```

## Functions as parameters

>- Being able to store a function in a variable makes it really simple to pass the function into another function. A function that is passed into another function is called a callback.

>- Let's say you had a helloCat() function, and you wanted it to return "Hello" followed by a string of "meows" like you had with catSays. Well, rather than redoing all of your hard work, you can make helloCat() accept a callback function, and pass in catSays.

```
// function expression catSays
let catSays = function(max) {
  let catMessage = "";
  for (let i = 0; i < max; i++) {
    catMessage += "meow ";
  }
  return catMessage;
};

// function declaration helloCat accepting a callback
function helloCat(callbackFunc) {
  return "Hello " + callbackFunc(3);
}

// pass in catSays as a callback function
helloCat(catSays);
```

## Functions as parameters

>- A function that is passed into another function is called a __callback__.
>- Let's say you had a helloCat() function, and you wanted it to return "Hello" followed by a string of "meows" like you had with catSays. Well, rather than redoing all of your hard work, you can make helloCat() accept a callback function, and pass in catSays.

```
// function expression catSays
let catSays = function(max) {
  let catMessage = "";
  for (let i = 0; i < max; i++) {
    catMessage += "meow ";
  }
  return catMessage;
};

// function declaration helloCat accepting a callback
function helloCat(callbackFunc) {
  return "Hello " + callbackFunc(3);
}

// pass in catSays as a callback function
helloCat(catSays);
```

### Inline function expressions
>- A __function expression__ is when a function is assigned to a variable. In JavaScript, this can also happen when you pass a function inline as an argument to another function. Take the favoriteMovie example for instance:

```
// Function expression that assigns the function displayFavorite
// to the variable favoriteMovie
let favoriteMovie = function displayFavorite(movieName) {
  console.log("My favorite movie is " + movieName);
};

// Function declaration that has two parameters: a function for displaying
// a message, along with a name of a movie
function movies(messageFunction, name) {
  messageFunction(name);
}

// Call the movies func, pass in the favoriteMovie function and name of movie
movies(favoriteMovie, "Finding Nemo");


>>> My favorite movie is Finding Nemo
```

But you could have bypassed the first assignment of the function, by passing the function to the movies() function inline.

```
// Function declaration that takes in two arguments: a function for displaying
// a message, along with a name of a movie
function movies(messageFunction, name) {
  messageFunction(name);
}

// Call the movies function, pass in the function and name of movie
movies(function displayFavorite(movieName) {
  console.log("My favorite movie is " + movieName);
}, "Finding Nemo");


>>> My favorite movie is Finding Nemo
```

### Why use anonymous inline function expressions?

>- Using an anonymous inline function expression might seem like a very not-useful thing at first. Why define a function that can only be used once and you can't even call it by name?

>- Anonymous inline function expressions are often used with function callbacks that are probably not going to be reused elsewhere. When you know the function is not going to be reused, it could save you many lines of code to just define it inline.

# Arrays

>- Array is a data structure that has the ability to store data more efficiently
>- The two most common methods for modifying an array are push() and pop().

## Push

>- You can use the push() method to add elements to the end of an array.

```
let donuts = ["glazed", "chocolate frosted", "Boston creme", "glazed cruller", "cinnamon sugar", "sprinkled"];
```

>- you can push donuts onto the end of the array using the push() method.

```
donuts.push("powdered"); // pushes "powdered" onto the end of the `donuts` array

>>> 7

console.log(donuts);

>>> ["glazed", "chocolate frosted", "Boston creme", "glazed cruller", "cinnamon sugar", "sprinkled", "powdered"];
```

>- Notice, with the push() method you need to pass the value of the element you want to add to the end of the array. Also, the push() method returns the length of the array after an element has been added.

## Pop

>- you can use the pop() method to remove elements from the end of an array.
>- Also, pop() returns the element that has been removed in case you need to use it.

```
let donuts = ["glazed", "chocolate frosted", "Boston creme", "glazed cruller", "cinnamon sugar", "sprinkled", "powdered"];

donuts.pop(); // pops "powdered" off the end of the `donuts` array
donuts.pop(); // pops "sprinkled" off the end of the `donuts` array
donuts.pop(); // pops "cinnamon sugar" off the end of the `donuts` array

>>> "cinnamon sugar"

console.log(donuts);

>>> ["glazed", "chocolate frosted", "Boston creme", "glazed cruller"];

```

## Splice

>- splice() method allows you to add and remove elements from anywhere within an array.
>- splice() lets you specify the index location to add new elements, as well as the number of elements you'd like to delete (if any).

```
let donuts = ["glazed", "chocolate frosted", "Boston creme", "glazed cruller"];

donuts.splice(1, 1, "chocolate cruller", "creme de leche"); // removes "chocolate frosted" at index 1 and adds "chocolate cruller" and "creme de leche" starting at index 1

>>> ["chocolate frosted"]

console.log(donuts);

>>> ["glazed", "chocolate cruller", "creme de leche", "Boston creme", "glazed cruller"]
```

>- The _first argument_ represents the __starting index__ from where you want to change the array.
>- the _second argument_ represents the __numbers of elements to remove__.
>- the _remaining arguments_ represent the __elements to add__.

>- `shift()` will remove the first element from an array.
>- `splice()` can be used if you specify the index of the first element, and indicate that you want to delete 1 element.
>- You can combine the elements in an array to form a string using the `join()` method.

## Array Loops

>- Once the data is in the array, you want to be able to efficiently access and manipulate each element in the array without writing repetitive code for each element.

```
let donuts = ["jelly donut", "chocolate donut", "glazed donut"];

donuts[0] += " hole";
donuts[1] += " hole";
donuts[2] += " hole";

console.log(donuts);

>>> ["jelly donut hole", "chocolate donut hole", "glazed donut hole"]
```

>- To loop through an array, you can use a variable to represent the index in the array, and then loop over that index to perform manipulations.

```
let donuts = ["jelly donut", "chocolate donut", "glazed donut"];

// the variable `i` is used to step through each element in the array
for (let i = 0; i < donuts.length; i++) {
    donuts[i] += " hole";
    donuts[i] = donuts[i].toUpperCase();
}

console.log(donuts);

>>> ["JELLY DONUT HOLE", "CHOCOLATE DONUT HOLE", "GLAZED DONUT HOLE"]
```

>- In this example, the variable i is being used to represent the index of the array. As i is incremented, you are stepping over each element in the array starting from 0 until donuts.length - 1 (donuts.length is out of bounds).

### The forEach loop

>- The forEach() method gives you an alternative way to iterate over an array, and manipulate each element in the array with an inline function expression.
>- Using forEach() will not be useful if you want to permanently modify the original array.

```
let donuts = ["jelly donut", "chocolate donut", "glazed donut"];

donuts.forEach(function(donut) {
  donut += " hole";
  donut = donut.toUpperCase();
  console.log(donut);
});

>>> JELLY DONUT HOLE
    CHOCOLATE DONUT HOLE
    GLAZED DONUT HOLE
```

>- the forEach() method iterates over the array without the need of an explicitly defined index.
>- In the example above, donut corresponds to the element in the array itself. This is different from a for or while loop where an index is used to access each element in the array:

```
for (let i = 0; i < donuts.length; i++) {
  donuts[i] += " hole";
  donuts[i] = donuts[i].toUpperCase();
  console.log(donuts[i]);
}
```

#### Parameters

>- The function that you pass to the forEach() method can take up to three parameters that can be called element, index, and array.
>- The forEach() method will call this function once for each element in the array (hence the name forEach.)
>- Each time, it will call the function with different arguments.

>>- The __index parameter__ is the positions within the array (starting with zero).
>>- The __element parameter__ is the values found within the array when index is called.
>>- The __array parameter__ is the entire structure (data structure). It will get a reference to the whole array, if you wanted to modify the elements.

```
words = ["cat", "in", "hat"];
words.forEach(function(word, num, arr) {
  console.log("Word " + num + " in " + arr.toString() + " is " + word);
});

>>> Word 0 in cat,in,hat is cat
    Word 1 in cat,in,hat is in
    Word 2 in cat,in,hat is hat
```    

### map Loop

>- creating a new array from an existing array is simple with the map() method.
>- With the map() method, you can take an array, perform some operation on each element of the array, and return a new array.

```
let donuts = ["jelly donut", "chocolate donut", "glazed donut"];

let improvedDonuts = donuts.map(function(donut) {
  donut += " hole";
  donut = donut.toUpperCase();
  return donut;
});

console.log(donuts);

>>> ["jelly donut", "chocolate donut", "glazed donut"]

console.log(improvedDonuts);
>>> ["JELLY DONUT HOLE", "CHOCOLATE DONUT HOLE", "GLAZED DONUT HOLE"]
```

>- The map() method accepts one argument, a function that will be used to manipulate each element in the array.
>- In the above example, we used a function expression to pass that function into map(). This function is taking in one argument, donut which corresponds to each element in the donuts array.

## 2D Arrays
>- A box of donuts can resemble a two dimensional grid with rows and columns. You could use an array of arrays that has the name of each donut associated with its position in the box.

```
let donutBox = [
  ["glazed", "chocolate glazed", "cinnamon"],
  ["powdered", "sprinkled", "glazed cruller"],
  ["chocolate cruller", "Boston creme", "creme de leche"]
];
```

>- If you wanted to loop over the donut box and display each donut (along with its position in the box!) you would start with writing a for loop to loop over each row of the box of donuts:

```
let donutBox = [
  ["glazed", "chocolate glazed", "cinnamon"],
  ["powdered", "sprinkled", "glazed cruller"],
  ["chocolate cruller", "Boston creme", "creme de leche"]
];

// here, donutBox.length refers to the number of rows of donuts
for (let row = 0; row < donutBox.length; row++) {
  console.log(donutBox[row]);
}

>>> ["glazed", "chocolate glazed", "cinnamon"]
["powdered", "sprinkled", "glazed cruller"]
["chocolate cruller", "Boston creme", "creme de leche"]
```

>- Since each row is an array of donuts, you next need to set up an inner-loop to loop over each cell in the arrays.

```
for (let row = 0; row < donutBox.length; row++) {
  // here, donutBox[row].length refers to the length of the donut array currently being looped over
  for (let column = 0; column < donutBox[row].length; column++) {
    console.log(donutBox[row][column]);
  }
}

>>>
"glazed"
"chocolate glazed"
"cinnamon"
"powdered"
"sprinkled"
"glazed cruller"
"chocolate cruller"
"Boston creme"
"creme de leche"
```

# Objects

>- objects are a data structure in javascript that lets you store data about a particular thing, and helps you keep track of data by using a "key".
>- One way to create an object is to create a variable and assign it to a pair
   of curly brackets

```
let umbrella = {

};
```

>- objects have properties and things they can do, to add this information, you can define key value pairs for each piece of data, like defining a key property called color and its value is pink:

```                                         
let umbrella = {                           /\
  color: "gray",                          /  \
  is_open: false                         /____\  
}                                          ||
```

>- Opening the umbrella is a task you want the umbrella to be able to do, it's not a property which is an attribute that describes the umbrella.
>- Something the object can do is a method. A __method__ is just a function that is associated with an object.

```
let umbrella = {
  color: "gray",
  is_open: false,
  open: function() {
    if(umbrella.isOpen === true) {
      return "The umbrella is already open!";
    } else {
      return "Julie opens the umbrella";
    }
  }
}
```

>- typeof is an operator that returns the name of the data type that follows it in the form of a string:

>>- typeof "hello" // returns "string"
>>- typeof true // returns "boolean"
>>- typeof [1, 2, 3] // returns "object" (Arrays are a type of object)
>>- typeof function hello() { } // returns "function"

## Object-literal notation

```
let sister = {
  name: "Sarah",
  age: 23,
  parents: [ "alice", "andy" ],
  siblings: ["julia"],
  favoriteColor: "purple",
  pets: true
};
```

>- The syntax you see above is called object-literal notation.
>- The "key" (representing a property or method name) and its "value" are separated from each other by a colon
>- The key: value pairs are separated from each other by commas
>- The entire object is wrapped inside curly braces { }.
>- The key in a key:value pair allows you to look up a piece of information about an object. Here's are a couple examples of how you can retrieve information about my Julia's sister's parents using the object you created.

```
// two equivalent ways to use the key to return its value
sister["parents"] // returns [ "alice", "andy" ]
sister.parents // also returns ["alice", "andy"]
```

>- `sister["parents"]` is called __bracket notation__ (because of the brackets!)
>- `sister.parents` is called __dot notation__ (because of the dot!).

## What about methods?

```
let sister = {
  name: "Sarah",
  age: 23,
  parents: [ "alice", "andy" ],
  siblings: ["julia"],
  favoriteColor: "purple",
  pets: true,
  paintPicture: function() { return "Sarah paints!"; }
};

sister.paintPicture();
>>> "Sarah paints!"
```

>- you can access the name of my sister by accessing the name property:

```
sister.name
>>> "Sarah"
```

## Object literals, methods, and properties
>- You can define objects using object-literal notation:

```
let myObj = {
  color: "orange",
  shape: "sphere",
  type: "food",
  eat: function() { return "yummy" }
};

myObj.eat(); // method
myObj.color; // property
```

## Naming conventions

>- Feel free to use upper and lowercase numbers and letters, but don't start your property name with a number.
>- You don't need to wrap the string in quotes! If it's a multi-word property, use camel case. Don't use hyphens in your property names

```
let richard = {
  "1stSon": true;
  "loves-snow": true;
};

richard.1stSon // error
richard.loves-snow // error
```

# Why does jQuery exists

>- By using Vanilla JavaScript to insert an element into the DOM, extra steps need to be taken:

  1. Creating an element:
`let div = document.createNode('div');
`

  2. Setting attributes and content of the new node:
`
div.innerHTML = "Hello Julie";
`

  3. Select the soon-to-be parent of the new node:
`
let parent = document.querySelector('#parent');
`

  4. and then finally, inserting the new node as a child of the parent node:
`
parent.appendChild(div);
`

>- But with jQuery, all of those steps are simplified to a one line of code:
`
$('#parent').append("<div>Hello Julie</div>");
`

## What is the $ sign?

>- With jQuery, the dollar sign is just a pointer to the JavaScript object that represents jQuery:

```
//Head over to the javascript developer tools in your browser (chrome in this):
//go to udacity.com, and type in jQuery in the console:

>>> function (e, t) { return new x.fn.init(e, t, r)}
```

>- the previous code means that jQuery is an object (or a function) of JavaScript.
>- If I type in the dollar sign ('$'):

```
> $
>>> function (e, t) { return new x.fn.init(e, t, r)}
```

>- With jQuery, the dollar sign is just a pointer to the same JavaScript object
>- jQuery returns an array-like object called __jQuery collection__, but this object has additional special methods.

```
$(string);        $(function);          $(DOM element);           $.ajax()

$("#foo");
>>> []
```

>- a string, function, DOM element can be passed (this passed arguments are called jQuery __selectors__) and a jQuery collection of DOM elements will be returned; you can call methods directly on the jQuery object like `$.ajax()` which subtracts away all the annoying nuances of ajax into a simple method called on the jQuery object
>- you can use jQuery to select a collection of DOM elements based on tag name, class, or ID:

```
$('tag');
$('.class');
$('#id');
```

### Important jQuery Selectors

<table>
    <tr>
        <td>Selector</td>
        <td>Sample</td>
        <td>Description</td>
    </tr>
    <tr>
        <td> (wild card \* ) </td>
        <td> $(' * ') </td>
        <td>all elements</td>
    </tr>
    <tr>
        <td>#id</td>
        <td>$('#div')</td>
        <td>element with id="div"</td>
    </tr>
    <tr>
        <td>.class</td>
        <td>$('.div')</td>
        <td>all elements with class="div"</td>
    </tr>
    <tr>
        <td>element</td>
        <td>$("p")</td>
        <td>all ```<p>``` elements</td>
    </tr>
    <tr>
        <td>el1, el2, el3</td>
        <td>$("h1,h2,h3")</td>
        <td>all ```< "h1" >, < "h2" >, < "h3" >``` elements</td>
    </tr>
    <tr>
        <td>:first</td>
        <td>$("h1:fist")</td>
        <td>first < "h1" > element</td>
    </tr>
    <tr>
        <td>:first-child</td>
        <td>$("b:fist-child")</td>
        <td>all < 'b' > that are the 1st child of their parent</td>
    </tr>
    <tr>
        <td>:last</td>
        <td>$("h1:last")</td>
        <td>last < "h1" > element</td>
    </tr>
    <tr>
        <td>:last-child</td>
        <td>$("b:last-child")</td>
        <td>all < 'b' > elements that are the last child of their parent</td>
    </tr>
    <tr>
        <td>:nth-child(n)</td>
        <td>$("div:nth-child(2)")</td>
        <td>all < "div" > elements that are 2nd child of their parent</td>
    </tr>
    <tr>
        <td>parent > child</td>
        <td>$("div > p")</td>
        <td>all < "p" > elements that are a direct child of a < "div" > element</td>
    </tr>
    <tr>
        <td>parent descendant</td>
        <td>$("span p")</td>
        <td>all < "p" > elements that are descendants of a < "span" > element</td>
    </tr>
    <tr>
        <td>:eq(index)</td>
        <td>$("ul li:eq(2)")</td>
        <td>the 3rd element in a list (index starts at 0)</td>
    </tr>
    <tr>
        <td>:contains(text)</td>
        <td>$(":contains('solo')")</td>
        <td>all elements which contain the text 'solo'</td>
    </tr>
    <tr>
        <td>[attribute]</td>
        <td>$("[src]")</td>
        <td>all elements with a src attribute</td>
    </tr>
    <tr>
        <td>:input</td>
        <td>$(":input")</td>
        <td>all input elements</td>
    </tr>
    <tr>
        <td>:text</td>
        <td>$(":text")</td>
        <td>all input elements with 'type="text"'</td>
    </tr>
</table>









# Links of interest!
>- <p>Web deployment platform: <a href="https://www.udacity.com/course/deploying-applications-with-heroku--ud272">Deploying apps with Heroku | Udacity</a></p>
>- <p>ECMAScript 6, or ES6's updates to JS language: <a href="https://www.udacity.com/course/es6-javascript-improved--ud356">ES6 - JavaScript Improved | Udacity</a></p>
>- <p> Collection of JS utilities for the intermediate to advanced JS developer: <a href="https://mootools.net/">Mootools</a></p>
>- <p> Make asynchronous requests in JavaScript: <a href="https://www.udacity.com/course/intro-to-ajax--ud110">Intro to Ajax | Udacity</a></p>
>- <p> A fast, small, and feature-rich JavaScript library: <a href="http://api.jquery.com/">jQuery</a></p>
