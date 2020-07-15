# pear :pear:
Pear is a framework project focused on e-commerce. 
Developed to reduce time and costs in the production of basic web sites.

The project is in pre-Alpha phase, so it is not recommended to use the templates that will be uploaded, as they are not stable and are subject to correction.

The use of the new classes and tools for development will be explained in the documentation.

_____________________________________________________________________________________________________________________________________________________________

Pear is a framework designed to be used completely, but if you want to use only one function of it you must copy its respective parts from the HTML and CSS files.

For a better experience it's recommended to use the Normalize.css library

Following you will see the ways to customize this framework in each of its parts using the pear.css file.

__________________________________________________________________________________________________________________________________________________________

HEADER

Changes can be made in classes:
'.header-box', by adding the following letters: <br>
-z: To remove the generic characteristics <br>
-b: No generic characteristics and with a black background color <br>
-c and -d: are equal to -b but with blue(-c) and red(-d) background <br>

	Example:
	'<section class="header-box-z">'

'.header-container', changes in this class have a recommendation as there are only two options:<br>
1.header-container: it has a grid-template-row of 150px 60px. Recommended for use with the generic style. <br>
2.header-container-b: it has smaller dimensions, it is recommended to use it with the non-generic classes of header box, 
  because if grid-template-row is 80px 60px.
  
  	Example:
	'<figure class="header-container-b">'

In the class '.container-image' the options are dictated by your previous choice in the class '.header-container': <br>
-If you chose .header-container you must use the .container-image class <br>
-If you chose .header-container-b you must use the class .container-image-b <br>

	Example:
	'<img class="container-image-b">'

Buttons of type 'a' have three kinds <br>
.a: Which is white with gray letters and its default :hover in green. <br>
.a-b: Recommended for dark themes since its letters are in white. It has no :hover set. <br>
.a-c: With a black lettering color. You don't have : hover configured

	Example:
	'<a class="a-b">'
	'<a class="a-z">'

  The configuration of the :hover should be done as follows:

	1. The :hover does not work with the generic configuration.

	2. Switch to .a-b or .a-c class

	This is how you can add the :hover
	"<a class="a-b b">"

	There are two types of :hover to choose from
	1. Complete buttons: 
  	- b
  	- f
  	- g
	2. Buttons with top border only
  	- c
  	- d
  	- e
  	- h
_____________________________________________________________________________________________________________________________________________________________________________

MAIN

The main one is divided into several sections that include the following:

  Hero where the presentation image is located this section gives the user two options for the size of the 
  image they wish to present, these are differentiated by the  
  high that the image will have, the way to use it is
  the next one:
  	
	Example:
	<figure class="imageContainer">
	<figure class="imageContainer-b">
	
  The '.prom' section is characterized by the fact that it is the part that has the first hookup to the customers, with strong discounts on the products.
  And that is where we will find 4 options for use, two of them as small labels and the others as large labels that cover the width of the image.
  For now there are only two colors to choose from among the labels: Black and yellow.
  
  The classes we can use are '.prom-desc' and '.prom-desc-b' which are small labels. And the big labels are the classes '.prom-desc-c' and '.prom-desc-d'
  
  	Example:
	<article class=".prom-desc">
	<article class=".prom-desc-d">
	
	
	

ATTENTION: "This work as specified in its license does not give warranties, it only gives recommendations and ways to use it correctly, to avoid errors".
