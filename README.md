# pear :pear:
Pear is a framework project focused on e-commerce. 
Developed to reduce time and costs in the production of basic web sites.

VERSION ALPHA

The project is in Alpha phase, you can use the templates you find, as long as you use the Alpha version. Changes and improvements for the BETA version
will continue to be uploaded and the use of files that do not correspond to the version may cause problems in the documentation

The use of the new classes and tools for development will be explained in the documentation.

_____________________________________________________________________________________________________________________________________________________________

Pear is a framework designed to be used completely, but if you want to use only one function of it you must copy its respective parts from 
the HTML and CSS files.

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
  
  These labels are linked with the class label '<a>' which has two options for the color of the text with '.prom-link' (Black) and '.prom-link-b' (White
  
  	Example:
	<article class=".prom-desc">
	  '<a class="prom-link">'
	</article>
	
	<article class=".prom-desc-d">
	  '<a class="prom-link-b">'
	</article>
	
  The '.gadgets' section only has options to change the overlay. Which varies in two colors which are Black or White.
  The way to choose the colors is as follows:
  
  	Example:
	<article class="gadgets-overlay">
	
	<article class="gadgets-overlay-b">
	
	
  The '.discount' section is intended to allow our customer to enter discount codes before making a purchase. And with it collect personal data to send 
  promotions via email and this retain the customer.
  
  Therefore we note the importance of offering a variety of options in the styles of the data collection box.
  The general color styles in this box are 3 which are: '.discount-grid' (Black), '.discount-grid-b' (Red), '.discount-grid-c' (Blue).
  	
	Example:
	<form class="discount-grid">
	<form class="discount-grid-b">
	<form class="discount-grid-c">
  
  With this variety of colors in the data collection box, we notice that a variety of buttons are also needed to choose from, of which there are 4.

  The buttons to choose from start with: '.discount-button' (Green), '.discount-button-b' (White), '.discount-button-c' (White borders), '.discount-button-d' (White top border)
  
  	Example:
	<button class="discount-button">
	<button class="discount-button-b">
	<button class="discount-button-c">
	<button class="discount-button-d">
	
_________________________________________________________________________________________________________________________________________________________________________________

FOOTER

The footer is divided into two sections, but only one of them (the last one) has modification options. 

  The styles of the footer should be the same as the colored Header to maintain a nice style. These colors are: '.credits-box' (generic), '.credits-box-b' (Black),
  '.credits-  box-c' (Blue), '.credits-box-d' (Red).
  
  	Example: 
	'<div class="credits-box">'
	'<div class="credits-box-b">'
	'<div class="credits-box-c">'
	'<div class="credits-box-d">'

  There is also an option without styles which is: '.credits-box-z' (White) but it must be linked to '.credits-link-z' (Black to the letters)
  
  	Example:
	'<div class="credits-box-z">'
	  '<a class="credits-link">'
	  

____________________________________________________________________________________________________________________________________________________________________________

RESPONSIVE

Responsive styles are not changeable and will be adapted generically without options. 

It is recommended to call the mobilepear.css file to have the responsive available. Otherwise you will have to create it. 

A mobile.md file was created that will indicate the instructions for use and the additions that you will be able to see on each screen

In the second version of Pear, options for responsive styles will be added.


_________________________________________________________________________________________________________________________________________________________________
_________________________________________________________________________________________________________________________________________________________________

PHONE.HTML

Phone.html is characterized by its simplicity for product demonstration, because the style options are limited for the first version.

In this page we will only find two classes that can be customized.

_________________________________________________________________________________________________________________________________________________________________

MAIN

The only customizations of this page are in the MAIN, the HEADER and the FOOTER share the classes and styles with Index.html

  The first class that can be modified is '.phone-button'. Which has 5 options for customizing the purchase button, from which you can choose these styles: 
  '.phone-button'(generic and default), '.phone-button-b'(Red button), '.phone-button-c'(Blue button) '.phone-button-d' (Button only with bottom border) and 
  '.phone-button-z' (Green button)

	Example: 
	<button class="phone-button">
	<button class="phone-button-b">
	<button class="phone-button-c">
	<button class="phone-button-d">
	<button class="phone-button-z">

  The second class that can be modified is '.partners-image' It is recommended that the images that are associated have some measures of 600x600px
  or 700x353px so that they can be adapted to the styles.

  The class choices are 2. The first '.partners-image' for images at 1:1 scale, the second '.partners-image-b' for images at 5:3 scale.

	Example: 
	<img class="partners-image">
	<img class="partners-image-b">

______________________________________________________________________________________________________________________________________________________________________
______________________________________________________________________________________________________________________________________________________________________
MODEL.HTML

The 'model.html' page is the place where the purchase will be processed and can be used as a global template for the styles you want to add in other situations, 
the modification of this is simple.

Payment gateways are not implemented by default, as they must be designed and added by the programmer who wants to use Pera. The only thing you will see is a page 
to confirm the payment and that leads to Paypal, but nothing can be done because the Paypal button must be configured individually in each case that you use a 
frame of any kind.

______________________________________________________________________________________________________________________________________________________________________
MAIN

In this page the changes differ from the general one only in the main one, since the header and footer remain unchanged.
  
  The only change they will be able to make to the section is on the buy button, since Pear version 1.0.0 will not incorporate more customizable.
  
  The buy button with the class: 'buy-button' has two groups of possible changes, among which are those that operate with the total background of the button as:
  '.buy-button' (green-generic), '.buy-button-b'(black), '.buy-button'(blue), '.buy-button'(red).
  
  	Example: 
	<button class="buy-button">
	<button class="buy-button-b">
	<button class="buy-button-c">
	<button class="buy-button-d">
	
  And the button that works only with the lower border: '.buy-button-e' (border-bottom: black)
  
  	Example:
	<button class="buy-button">

______________________________________________________________________________________________________________________________________________________________________
______________________________________________________________________________________________________________________________________________________________________

PAYNOW.HTML

This page is only a payment confirmation, since the bank gateway or paypal button settings must be configured and implemented by the user. The only thing Pear 
offers is styles for payment or cancel payment buttons.

The only modification you can make will be to the MAIN as it is a payment confirmation we focus on the user making the process without distractions.
_______________________________________________________________________________________________________________________________________________________________________

MAIN

  The styles you can add to the payment button are two groups, the first group with the full button: '.pay-button'(green-generic), '.pay-button-b'(black), 
  '.pay-button-c'(blue).
  
  	Example:
	<button class="pay-button">
	<button class="pay-button-b">
	<button class="pay-button-c">
	
  The second group of styles for the payment button has only the bottom edge of the button: '.pay-button-d'(border-button: green), 
  '.pay-botton-e'(border-bottom: black).
  
  	Example:
	<button class="pay-button-d">
	<button class="pay-button-e">
	
  For the don't pay button we will only have a group of styles with the full button and colors not to draw attention: '.dontpay-button'(red-generic), 
  '.dontpay-button-b'(black), '.dontpay-button-c'(white)
  
  	Example:
	<button class="dontpay-button">
	<button class="dontpay-button-b">
	<button class="dontpay-button-c">
	
__________________________________________________________________________________________________________________________________________________________________________
__________________________________________________________________________________________________________________________________________________________________________

ACCESORIES.HTML

The accesories.html page, being a site destined to the user's purchase, handles the same base styles of phone.html. As well as the purchase confirmation 
is the same as model.html.

The only options to be modified are in the MAIN of this page since it does not have a visible purchase button, this can only be seen by the user when 
placing the cursor over the product.

_________________________________________________________________________________________________________________________________________________________________________

MAIN

  When the user positions the cursor over the image of the product, he will be able to see the prices, the recommended options for this is if: 
  The image has a white background, use the class '.accessories-price'(black background with opacity 0.6) and if the image has a dark background,
  use the class '.accessories-price-b'(white background with opacity 0.6).
  	
	Example:
	<div class="accesories-price">
	<div class="accesories-price-b">

___________________________________________________________________________________________________________________________________________________________________________
___________________________________________________________________________________________________________________________________________________________________________

GADGETS.HTML

The page gadtgets.html is based on simplicity, since the purchase of these low price items, must be fast so its simplicity and attractiveness are fundamental.

___________________________________________________________________________________________________________________________________________________________________________

MAIN

  The only elements that can be customized are the classes '.gadts-content'( must go with the article element with the class '.gadts-desc') and 
  '.gadts-content-b'( must go with the article element with the class '.gadts-desc-b')
  
  	Example:
	<div class="gadts-content">
	  <article class="gadts-desc">
	  
	<div class="gadts-content-b">
	  <article class="gadts-desc-b">
	  
__________________________________________________________________________________________________________________________________________________________________________
__________________________________________________________________________________________________________________________________________________________________________

SERVICES.HTML

This page does not have built-in style customization in the ALPHA and BETA versions, in version 1.0.0 they will be added.
	




ATTENTION: "This work as specified in its license does not give warranties, it only gives recommendations and ways to use it correctly, to avoid errors".
"This work is part of my portfolio and I make it to practice css vanilla, is not a framework with support from large companies, the next versions will bring 
 significant improvements, for the moment if it works for you use it freely, if not use only some properties that I can offer and complete it with a more 
 complete and complex framework."
