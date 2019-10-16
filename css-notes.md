# CSS Notes
## What exactly does CSS do?
> CSS is the next step after HTML, it's time to bring your website to life! CSS is used to make visual changes to your page that are not possible within HTML. Some of the possibilities include...
    - Adding color to everything
    - Changing font style and size
    - Images
    - Borders, etc...

## Colors in CSS
> When using the colors in CSS there are a few ways to access colors...

    1. Basic Color Names
         color="red"
> If you just need a color, perhaps for educational or testing purposes, just put the name of the color. There are lots of different colors to choose from although it could be quite cumbersome if your trying to find a specific color, I would rather use one of these next techniques...

    2. Hexadecimal RGB
            #66cdaa
> While the above example looks un-readable its actually not hard to figure it out if you break it down.

 First you must understand the range of colors using numbers and some letters to determine the amount of color inputted. The range is as follows...
***    
> Smallest | 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, a, b, c, d, e, f | Largest.
***
Now lets understand the seven digit code.
- `#` = letting CSS know your using hex-color.
- `66` = Red
- `cd` = Green
- `aa` = Blue

Below is the output of this color!

![teal color](images/teal.png)

    3. RGB Values
        rgb(102,205,170)
> If you understand hex-color then this one might appear more coherent but lets go over it...
- For rgb the range goes from 0-255.
- rgb = Telling CSS your using rgb method
- `102` = Red
- `205` = Green
- `170` = Blue

        4. RGBA
            rgba(0,255,0,.5)
> RGBA is simply adding an opacity setting to your rgb. The rgba code above would create a saturated green thats been brought to 50% transparency!
