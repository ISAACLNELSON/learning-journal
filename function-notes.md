# Function Notes
Creating and calling functions is the best method to use Javascript within webpages. using functions increases javascript modularity significantly, reducing the amount of times that you have to type out a specific line of code to just once, then just call that code again whenever you need it. there are more ways to increase efficiency using javascript and functions, for instance consider this code...

    var a = 1; 
    function example(){
            if (a > 0 && a < 10){
                document.getElementById('exampleID').style.border = "4px solid red";
            } else if (a > 9 && a < 20){
                document.getElementById('exampleID').style.border = "4px solid blue";
            } else {
                document.getElementById('exampleID').style.border = "4px solid green";
            }
        }
        example();

this function takes variable 'a' and depending on the value turns an element with the id 'exampleID' and gives it a border of the corresponding color.(if it works...)
this can be optimized in a few ways, consider this

    var a = 1
    var ex = document.getElementById('exampleID');
    var  example = (function(){
        if (a < 10){
            ex.style.border = "4px solid red";
        } else if(a < 20){
            ex.style.border = "4px solid blue";
        } else {
            ex.style.border = "4px solid green";
        }
    }());

what changed? 
- we stuffed document.getElementById('exampleID') into a var called ex. much faster.
- we created a var called example and assigned it the function we made while at the same time having it run automatically to to the last set of paretheses. 
- and finally we removed the && operator because of the way conditional statements work, we took advantage of that... 