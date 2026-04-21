# html

Block Elements :A block element always starts on a new line and takes the full width available.

Key Points
->Starts on a new line<br>  
-> Takes full width<br>  
-> Can contain block + inline elements.<br>  

->  Block elements take full width and  start on the next(new) line

Block Tags: 
div                     <br>
p                     <br>
h1 - h6                     <br>
section                     <br>
article                     <br>
footer                      <br>
header                      <br>
nav                     <br>
ul                      <br>
li                      <br>
table                     <br>


Inline Elements : Inline elements does not start on a new line and 
take only as much width as needed .

Key Points :
-> Stay in the same line. <br>  
->Takes only required width.<br>  
->Cannot contain bloack elements(usually)<br>  
-> take the required width and stay in the same line.

Inline tags :
span                                      <br>                      
a                                       <br>
img                                       <br>
strong                                      <br>
em                                      <br>
b                                       <br>
i                                       <br>
u                                       <br>
small                                       <br>
label                                       <br>



Doctype ->It is not an HTML tag, it's just a declaration that tells the browser, use modern html5 standards to render this page.

Doctype = "text” why does it still works ?? 
Ans -> Because the browser ia very forgiving .
Reason : Because of the error-tolerant parsing 
(they try their best to show the code even if code is wrong)
my -(means even if the code is wrong browser still try its best to show it, )

<Doctype html> -> Standards browser 
Follows modern HTML & CSS rules
consistent behavior across browsers
(html and css behave normally )


(Wring or missing)<Doctype text > -> Browswe switches to Quriks mode
Mimics old broswer behavior (like old internet explorer)
css behave wierdly.
(inconsistent )

problems : - margin and padding may act differently 

Layout might break unexpectedly

Css widths behave incorrectly

Relative (image) Path: 
A relative path points to an image based on your current file location(project folder)
img src ="img/photos.png"

How it works 

./ -> current folder 

../ -> one folder up

No / -> same folder


When to use : 

-> Inside your project

-> Local development

-> When files move together

-> Portaility : high 

-> Based on current file location

-> Usage: Locale images 

Absolute Path : An absolute path gives the full URL or full system path to the image

ex: img src = "https://example.com/image.jpg
src = "/images/pic.jpg"

Types : 
Full Url

Points to another website

Root Path (starts with /)

-> Starts from website root

COMMON MISTAKE:

img src = "C\Users\me\Dekstop\img.jpg"

This will only only work on your computer
It will break on other devices or servers 


IMP:

Use relative paths for your own assests

Use absolute URL's for: 

-APIs

-CDN images

-External resources