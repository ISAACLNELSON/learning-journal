# Layout, Links, Functions

## Layout
Layout is very important in a web page, it is manipulated with CSS. There are lots of types of ways to position your boxes in your layout..
- Normal flow, this is the default boring look, with Normal flow you wouldnt be able to naturally place items side by side or anything interesting looking
- Relative positioning, this is used when you want to adjust an item based on where it naturally lies in the layout. i.e move this box left 5 pixels.
- Absolute positioning, this effect sets items down in relation to the browser window, unlike relative which adjusts based on its current location.
- Overlapping elements, this is acheived or avoided by manipulating the z index, as in x, y, and z. z being the third dimension.
- Floating elements, last but not least is the float mechanic, this acheives perhaps the most natural positioning of items on the page. Place a paragraph and an img in the same div in your html and you'll be able to float one left and the other right and they will naturally sit side by side within your div box!

 # Links
Link to outside url

        `<a href="www.google.com">Click here to go to Google!</a>`
Link to another page on your site

        `<a href="about.html">Learn about me here!</a>`
Link to a spot on your page

        `<a href="#top">Take me back to top of this page.</a>`

# Function basics
Now that we know asome basics to Javascript im glad were finally learning about functions, wrapping your code in a function can make it so much easier to implement OR choose not to implement if need be! 
 ## Anatomy of the function

        function sayHello(){
            var hey = 'Hello'
            console.log(hey);
        }
        var hey = 'banana';
        sayHello()

* note you must 'invoke' the function after you have created or else it will never be used!
* also everything within the function is whats called local. in other words both hey variables are valid because the one in the function is local and the one outside is global.