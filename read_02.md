# Html, CSS, & JS Notes II
## Text in Html
    There are 6 levels of headers..
# `<h1>`
## `<h2>`
### `<h3>`
#### `<h4>`
##### `<h5>`
###### `<h6>`
    More common tools

`<p>`  |  paragraph tag, used to seperate a block of text.
***
`<b>`  |  Bold tag, Makes text **bold**
***
`<i>` | Italic tag, makes text *italic*
***
`<sup>` | Sup element, used to contain characters that are superscript i.e the 2 in E=MC^2.
***
`<sub>` | Sub element, used to contain characters that are subscript i.e the 2 in H2O.
***
`<br>` | break tag, creates a new line in the text.
***
`<hr>` | Horizontal rule tag, creates a horizontal line to seperate the text.
***
# CSS

## Thinking inside the box.

CSS is the paint on the house. You can paint certain sections, make the inside and outside different colors, add some trim paint or a border, Or just paint ***Everything*** the same color. 

You use the terms you learned for html in CSS. When you refer to something in CSS for example `<p>` all paragraphs will be affected by wahtever changes you make. And by default everything starts out as a box, even if you dont see it once you add a border you will understand. 

## CSS terminology

The tool used to create changes in CSS are called declarations.
    
        p {
            font-family: Ariel;}
       This ^----------------^  is called a "Declaration"

All css declarations are comprised of property value pairs. seen below

        p {
            color: red;}
            ^---^  ^--^
          Property  Value


# JavaScript Notes
Javascript is the final piece of the web development puzzle. JS adds all the true functionality to a page, anything that requires logic, movement,data gathering, and much more. The possibilities with JS are endless.

Creating a JS file
Create a js file by adding .js to the end of a new file.

    - example: filename.js
Linking to HTML
You can link your js file to html by adding a script tag, this will create an inline link to the js file...

- example: <script src="js/filename.js"></script>
This will link the html to the logic and functions within the js file.
Javascript runs where you put it in HTML
simply wherever you place the script for your js file within your html, that is where you will find that on your webpage.

## JS terminology

script    |  a script is a series of statements.
***
statement  |  Statements are one line of code in JS usually ending in a semi colon.
***
variables | also seen as var, variables store various data types in them, strings, booleans, numbers, etc...
***
Array   | Arrays are simply lists in JS, You can store the same data types as a variable, you could even store variables!
***
