HTML Official website:
https://developer.mozilla.org/en-US/docs/Web/HTML
w3school
git token : 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

HTML 
=====
tags -> <htmnl> </html>
-> Header Tags 
===============
<h1> ,<h2>,<h3> ,<h4> , <h5> <h6>
Larger to smaller 
Ex:  <h1 style="color: rgb(237, 111, 100);">HTML 1</h1>

->Paragraph Tag
===============
<p></p>
example -> Lorem50 -> genrate dummy paragraph with 50 words 
![alt text](image-1.png)

Div Tag -> division 
====================


CSS Basics
===========
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
2)Un-Ordered List -> <ul></ul>   -> like dots/circle/square etc
3)List Items -> <li></li>

Ex: 
<ul type="square">

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
external url -> open in new tab  ->  target="_blank"
---------------
syntax -> 
<a href="https://google.com" target="_blank">Google</a>

href -> hiper text referance

internl url/part of website -> open in same tab
------------------------------
syntax-> 
   <a href="https://google.com">Google</a>

suppose you want to open some section of same page then use below 
-----------------------------------------------------------------
<a href="#contact">Contact US</a>      -> when you click on contactus it will go the id ="contact"
<p>rgfyqegfhukiehrkghkht</p>

    <div id="contact">
        <h2>Contact us</h2>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
    </div>


---------------------------------------------------------------------------------------------------------------------------
-Tables
=======
<table>  -> 
<thead>  ->heade section of table 
<th>   -> table header for each table {by default html give the content in bold letters        , but by using css we can convert it to normal}
<tbody>  ->body section of table 
<tr>   ->table row  
<td>   -> table data in table body {by default it is normal text (not bold letter)}
<rowspan> -> row span -> combine two or more rows 
<colspan> -> column span -> combine two or more column
Ex:  <th colspan="2">SKILLS & EXPERIENCE</th> -> span of two columns
-----------------------------------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------------------------------
-Forms -> collect informations from users  
==========================================

<form>  -> handling form data 
<input>  -> input elements of form - input type->>> submit, reset,text , password , email , data , time , range , color selection etc

syntax tag -> <input type="text">  -> control+space to get shortcut
----------
EX:
<label>Email</label>
<input type="email" placeholder="email"> -> placeholder is given to give name {email} inside the box

reset -> reset the form
submit -> submit the form 

<label>  -> to give the name for the field 
<select> -> to select like dropdown
<textarea> -> to add comments

-> <legend> ,<fieldset>
when we have very large form like some exam form then they have multiple field such as personal infomation , address , education etc such thing are writen in <fieldset> 
<fieldset> -> set of field called fieldset and heading to filedset given called as <legned>
----------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------
HTML 5 Tags
===========
<section>
<article>
<nav>   -> mostly contains the links (anchor tag) <a href='#'>Home</a>
<aside>
<header>
<footer>
<figcaption> -> mostly used for gallary
<figure> -> mostly used for gallary
<audio>
<video>
website -> webpage -> section -> div /article
for gallery below tag are used 
<figcaption>
<figure>

focus on syntax only not css part
---------------------------------------------------------------------------------------------------------------------