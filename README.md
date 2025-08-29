git token : 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
CSS
===
inline -> style attribute 
internal -> <style> tag -> <head>
external -> .css -> </head>

Note: 
attribute - which gives extra information about the tag Ex: Style atrribute
<h1 style="color: brown;"> Welcome to CSS</h1> 

inline ->    <h1 style="color: brown;"> Welcome to CSS</h1> 
------
internal -> attributes are given into head section
-------- 
<head>
    <title>CSS Basics</title>
    <Style>
        h1{
            color: black;
        }
    </Style>
</head>

external -> Mostly we are using this approach for websites , here we will create separate .css file and connect top our head section
---------

Selectors in CSS - > it is in key:value pair 
================
syntax:
selector{
	key:value;
	key:value;
}

shortcut for getting suggestion of tags ===>>   < + CTRL +SPACE 

Types 
1)tag selector -> h1{}
2)id selector -> #id{}
3)class selector -> .class{}

tag selector 
example->
        h1{
            color: black;
        }
id selector 
example->
<head>
    <title>CSS Basics</title>
    <Style>
        #html{
            color: blueviolet;
        }
        #css{
            color: red;
        }
        #js{
            color: yellow;
        }
    </Style>
</head>
<body>
    <h1 id="html">Welcome to HTML</h1>
    <h1 id="css">Welcome to CSS</h1>
    <h1 id="js">Welcome to Java Script</h1>
</body>

class selector->
<head>
    <title>CSS Basics</title>
    <Style>
        .red{
            color: red;
        }
        #js{
            color: yellow;
        }
    </Style>
</head>
<body>
    <h1 class="red">Welcome to HTML</h1>
    <h1 class="red">Welcome to CSS</h1>
    <h1 id="js">Welcome to Java Script</h1>
</body>



Style Properties 
===================
inside space = padding
outside space = margin
       h1{
        color: blue;
        background-color: pink;
        padding: 100px;
        margin: 100px;
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS';
        font-size: 200px;
       }4 
	  
List of items 
==============
Types 
1) Ordered list ->(numbers, alphabates)<ol></ol>
2)Un-Ordered List -> <ul></ul>
3)List Items -> <li></li>

Image Tag 
=========
no closing tag
syntax 
-----
<img src="" alt="">

src -> image location
alt -> if server is down then atleat name of the image is shown 


span Tag 
========
suppose i want two diffrent color for a word 
welcome -> wel-red , come-blue
  <h1>
        <span style="color: red;">Wel</span><span style="color:blue">come</span>
  </h1>
  
Anchor Tags /HTML Links -->  <a></a>
=======================

external url -> open in new tab 
---------------
syntax -> 
<a href="https://google.com" target="_blank">Google</a>

internl url/part of website -> open in same tab
------------------------------
syntax-> 
   <a href="https://google.com">Google</a>
suppose you want to open some section of same page then use below 


HTML 
=====

-Tables
-------
<table>  -> 
<thead>  ->heade section of table 
<th>   -> table header for each table 
<tbody>  ->body section of table 
<tr>   ->table row 
<td>   -> table data in table body 
<rowspan> -> row span -> combine two or more rows 
<colspan> -> column span -> combine two or more column

Forms -> collect informations from users  
------
<form>  -> handling form data 
<input>  -> input elements of form -> submit, reset,text , password , email , data , time , range , color selection etc
reset -> reset the form
submit -> submit the form 
syntax tag -> <input type="text">
<label>
<select> -> to select like dropdown
<textarea> -> to add comments
-> <legend> ,<fieldset>

HTML 5 Tags
===========
<section>
<article>
<nav>
<aside>
<header>
<footer>
<figcaption>
<figure>
<audio>
<video>