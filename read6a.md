## Dynamic web pages with JavaScript

HOW HTML, CSS,
& JAVASCRIPT FIT
TOGETHER  ??? 

- <html>
CONTENT LAYER
. html files 

- {css}
PRESENTATION LAYER
. css files 

- j avascri pt()
BEHAVIOR LAYER
.js files 

## CREATING A BASIC JAVASCRIPT 

JavaScript is written in plain text, just like HTML and CSS, so you do not
need any new tools to write a script. This example adds a greeting into an
HTML page. The greeting changes depending on the time of day. 


var today= new Date();
var hourNow = today.getHours();
var greeting;
if (hourNow > 18) {
greeting= 'Good evening!';
else if (hourNow > 12) {
greeting = ' Good afternoon!';
else if (hourNow > 0) {
greeting = 'Good morni ng!';
else {
greeting = 'Welcome! ' ;
document .write( ' <h3>' +greeting + ' </ h3> ');



### PLACING THE SCRIPT IN THE PAGE 

You may see JavaScript in the HTML between
opening <script> and closing </script> tags
(but it is better to put scripts in their own files). 


## Basic javascript instructions : 

- STATEMENTS 
- COMMENTS 


#### WHAT IS A VARIABLE?  

A script will have to temporarily
store the bits of information it
needs to do its job. It can store this
data in variables. 


### DATA TYPES 

- NUMERIC DATA TYPE 
- STRING DATA TYPE 
- BOOLEAN DATA TYPE 



#### USING A VARIABLE TO STORE A NUMBER 

var price;
var quantity;
var total;
price = 5;
quantity = 14;
total = price * quantity;
c02/j s/numeri c-vari ab 1 e .j s
var el = document.getElementByid( ' cost ');
el .textContent = '$' +total; 

*** and other uses for A VARIABLE :

## the end 