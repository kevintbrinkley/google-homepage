# google-homepage

Putting together HTML and CSS skills to deconstruct and put back together the google homepage.  After finishing this first chunk, I will assess whether to push on to the advanced section.

V0.1-- 
    -Google logo centered horizontally, and lowered vertically along the page to match google.com.  
    -Box added for search bar.  Centered just below google logo.  Rounded corners, and drop shadow.
    -Input box set to match height of search bar, and sets text to be gray and apropriate size.  *Note: Google search bar is black text. I like how gray looks.*
    -Input box has margins within larger search box to accomadate adding picture of magnifying glass and microphone.  Microphone will not be a functional button, beyond maybe adding a javascript alert message so it does *something*.
    -Next steps: add buttons below bar, create and add icons for magnifying glass and mic, make the header and footer.



v0.2--
So, I finished the page and was frustrated by how some elements repsonded to the page shifting in size.  Miniturizing the window, or opening and closing devtools, would change the spacing between my logo and bar.  In addition, by the end of the project I had become frustrated by how I had organized my content in the first attempt. My decision was to effectively re-do the whole thing.  I recreated the html, planning ahead this time: deliberating creating all of my divs, classes, and one id first.  Then I built the style working in order down the html in three primary parts (header, search, footer), attempting to organize each part of the style in order of occasion and importance in each section.  

The result is much smoother in my opinion.  

Images: The search and microphone icons are from google's android icon library.  
	I built the image for the google apps button in Pinta on Ubuntu.  

Features: 
--Every link/button leads somewhere, but none of the destinations are valid. Intent is to show that they COULD lead to their intended destination if I had a pag built.
--The search buttons have a shadow effect that comes up when the cursor is hovering over them.
--The search bar has a shadow effect that comes up when the cursor hovers and remains if the text field is selected.
--The microphone button displays an alert that voice search is not enabled (Javascript woo! Super basic script though.)
-- The screen can be resized and the dimensions between the logo, search bar, and buttons remains.
--Hard to demonstrate, but the header and footer are fixed, so they will remain in place as the rest of the page content scrolls.

This project was built with knowledge and basic instructions:
From The Odin Project's [curriculum](http://www.theodinproject.com/courses/web-development-101/lessons/html-css)


