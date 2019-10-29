# My favorite code from my project.

## In my project I used javascript to program some buttons. 

> Specifically when you press the button the corresponding box appears. 

## Javascript 

        function showData(){
        document.getElementById('dataBox').style.display =  'block';
    }
    function showCon(){
        document.getElementById('consultBox').style.display =   'block';
    }

    function showRep(){

        document.getElementById('reportBox').style.display = 'block';

    }

 

## HTML

    `<button type="button" id="data-button" onclick="showData() ">Data Management</button>`
    `<div id="dataBox">`
    `<h3>Data Management </h3>`
    `<img src=images/data-man.jpg>`
    `<article>`

(Above code its repeated for other buttons as well. )

 

CSS

    button {
        color: rgb(39, 35, 35);
    }
    button:hover {
        background-color: rgb(133, 133, 133);
        transition-duration: 0.4s;
    }
    #data-button {
        border: 3px solid rgb(47, 121, 150);
        border-radius: 40%;
        font-size: xx-large;
        width: 30%;
        height: 20%;
        position: absolute;
        top:410px; left: 65px;
    }

[check it out here](https://isaaclnelson.github.io/102-project/)