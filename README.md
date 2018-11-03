## First HTML site - Lifting
* [General info](#general-info)
* [The content of the task](#the-content-of-task)
* [Technologies](#technologies)
* [Tools](#tools)
* [Screen](#screen)
* [Working Page](#working-page)

## General info
First HTML site - lifting

## The content of the task
* Start by copying the code from the previous task and pasting it into the project in the index.html file.
* Pin the style.css file.
* In the style.css file, write the selector for the <body> tag and add the braces {} after it
* Inside the rule created in this way (between buckles {}), use the background-color property to give 
the background for the whole page, eg # 2ecc71.
* Go to index.html for a moment. Inside the <body> element, create a <div> tag with the content class 
(class = "content") and place its closing counterpart (</ div>) just before the </ body> tag. This way, 
the entire page content will be inside div element. This will be our container :)
* Return to the style.css file and create a rule for the newly added item in it, reaching for it using its class.
* Within the new rule, limit the width of our container (i.e. the previously mentioned div tag with the content 
class to store other elements) up to 500px.
* Additionally, give it a margin, thanks to which it will be centered horizontally (margin: 0 auto, more on 
this practice you will learn in the next submodule).
* These are not all rules for our container :) Now give it a white background. For background-color use the values: 
white, rgb (255,255,255) or #FFF.bNow add a 20px padding.
* Create another rule, this time for the <h1> tag, and then center the text in it using the text-align property.
* Open the index.html file.
* Right before the <body> tag, before <div class = "content">, insert the page header. To do this, create a <div> tag 
with the header class. Remember to close it.
* Inside this tag, create a <h1> tag and put text that welcomes you on your page.
* Note that photos can go beyond our div about the content class. width: 100% for the <img> tag is a declaration that 
will solve our problem. The photos will now occupy 100% of the parent's width.
* The next step will be to create a footer. After closing the content class element, open the <div> tag with the 
footer class. Inside it, put a paragraph with the text "© [Your name and surname], 2018".
* Bravo! You have created an HTML skeleton for a simple page layout. It's time to add some life to your header and 
footer using CSS. Go to the style.css file. Using the body selector, set the margin of the entire page content to 0.
* The next step will be to sharpen the page header. Create a selector for it using the class assigned to it. Inside 
this selector give it the properties: text centering, 30px 0 padding, background color: # f39c12 and white text color.
* In this step you will take care of the polishing of the footer. Again, create a selector using the class you gave the 
footer. Enter in it the properties: background color # 7f8c8d, change all text to uppercase (you will do it with 
text-transform: uppercase) and bold font.
* To get a real footer on your site, focus on the text of the paragraph in it. Create a selector for it and make the 
margins 0, padding 30px on the top, 0 on the right, 15px on the bottom and 20px on the left.

## Technologies
Project is created with:
* HTML5

## Tools
The following tools were used
* Webstorm
* Git

## Screen 
![Screen](https://github.com/wojtekboj/module_1-1.2/blob/master/images/screencapture.png)

Link do Zadania 1.2
https://wojtekboj.github.io/module_1-1.2/index.html