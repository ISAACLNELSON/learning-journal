# Read #3 Loops, Boxes, and Lists.
## First lets go over lists in Html
## 3 types of lists in Html...
1. `<ul>` unordered list, or a bulleted list
2. `<ol>` ordered list, or a numbered list 
    - within both `<ul>` and `<ol>` the term for each line will be the `<li>` tag, this will contain the listed content.
3. `<dl>` definition list, 
    - within a definition list there will be 2 terms instead of `<li>`
    1. `<dt>` this tag contains the term being defined
    2. `<dd>` and this is where the actual definition will be

An example of an unordered list

        <ul>
            <li>
            ul stands for unordered list
            </li>
            <li>
            li stands for list item
            </li>
        </ul>

An example of an ordered list

        <ol>
            <li>
            ol stands for ordered list
            </li>
            <li>
            li stands for list item
            </li>
        </ol>

An example of an definition list

        <dl>
            <dt> Isaac Nelson </dt>
            <dd>
            A really cool guy!
            </dd>
        </dl>

# A brief overview of boxes in CSS
Every element in Html has its own box, using CSS you can manipulate these boxes in various ways to get the desired design. Some ways you can change them are..
- change the width/height
- background color
- font color
- font size / font-family
- Give it borders, change the border size, radius and color

The list goes on and on. Also i wanted to note that usually i would write it as code but in the case of discovering new ways to change CSS, ive found that it is incredibly intuitive. For instance if you have an idea on how you would like to change your boxes, go ahead and statr typing it out and most likely it will come up in the auto completion box. And if not all the knowledge you could ever want is only a Google search away!

# Loops in Javascript

## For loop.
The for loop is used to loop over  a set numerical value. It is great if you know how many times you need to iterate. Another option is using it to iterate over an array.
### Anatomy of the for loop

(start at this value)   
                | (run until this condition)
                |          |    (increment by...)
                V          V      V
            v--------v  v----v  v-v
        for (var i = 0; i < 10; i++) {
            console.log(i);
        }           ^
                    |       
                (do this once per iteration!)

[Table of Contents](README.md)