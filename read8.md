## comparison operators : 

Evaluating conditions 

== is equal to 
!= is not equal to

=== sirict equal to
!==  not sirict equal to

> greater rhan 
< less than 


### structuring comparison operators : 

(sorce >= pass)



## logical operators 

- logical && 
- logical or 
- logical not 

### USING LOGICAL AND 

ex : 


c04/js/ logical-and.js
var scorel = 8; II Round 1 score
var score2 = 8; II Round 2 score
var passl 6; II Round 1 pass mark
var pass2 = 6; II Round 2 pass mark
II Check whether user passed both rounds , store result in variable
var passBoth = (scorel >= passl) && (score2 >= pass2);
II Create message
var msg = 'Both rounds passed: ' + passBoth;
II Write the message i nto the page
var el = document.getElementBy!d( 'answer') ;
el.textContent = msg; 


## loops 

- for 
- while 
- do while 

ex : 
for (var i =0; i<10; i++)

^ initilization   ...> var i =0;
^ condition ...> i<10;
^ update ...> i++ 

## USING WHILE LOOPS 


This loop will continue to run
for as long as the condition in
the parentheses is true. That
condition is a counter indicating
that, as long as the variable
i remains less than 10, the
statements in the subsequent
code block should run


ex :
c04/ js/while-1oop.js JAVASCRIPT
var i = l ;
var msg = ' ' ;
II Set counter to 1
II Message
II Store 5 times tabl e in a variable
while (i < 10) {
msg += i + ' x 5 = ' + (i * 5) + '<br I>';
i++;
document .getEl ementByid( ' answer') . innerHTML = msg; 

### the end 