#--------------------------- CS50's Web Programming with Python and JavaScript – Project 0 ------------------------

#---- Otha Lewis CS50 - Project0 ----
My project0 site contains 7 files.  They are colorpicker.gif, index_p0.html, cs50_ol983_p1.html, cs50_ol983_p2.html, cs50_ol983_p3.html, 
variables.scss, variables.css.

To get the full experience of webpage development, I converted an old laptop to an Ubuntu 20.04 Linux server and upgraded my workstations 
to Windows 10 Pro.  This assignment can be accessed by clicking my new link, www.jaboteq.com. 

#---- index_p0.html ----
This is my index page and is the basic layout that is replicated throughout the project.  The source of the content, for this 
assignment, is my resume and I added an image, named colorpicker.gif, and linked to a stylesheet called variables.css.  There are 2 
unordered list on this page.  The first unordered list allows navigates the page reader to navigate the current page by using the id 
property.  The second list is the table of content and will allow you to circumvent the other three pages.

#---- cs50_ol983_p1.html ----
This page is builds on the structure of the index page and adds more Bootstrap assets such as the @media property.  This will allow the 
h1 header float in at 500px and an abbreviated header to float in 499px making the website mobile sensitive.  I also used blue floating 
blocks that move around as the web browser decreases or increases in size taking I consideration a mobile device.

#---- cs50_ol983_p2.html ----
Page 3, like page 2 capitalized on the basic structure of the index page.  This page, like the previous has linked to a css page.  I 
used the class property to link up with the css block ul.toc.  This css selector allowed me to turn off the unordered list bullets.  
Also, on this page, just like the all the others, there is an on page nav link that will take you back to the top of the page; just 
click on Back to Top.

#---- cs50_ol983_p3.html ----
The fourth and final page and the end of my resume.  Starting with the basic page like before I decide to use the ordered list but with 
lower-case letters.  I also constrained one of the headers and paragraphs to the SCSS nesting and applied the variables and inheritance 
to change the font and background color.

#---- Trouble – During Testing ----
I tested the website on MS Edge, Fire Fox, and Chrome and got different results.  That was because I am using JavaScript to navigate 
back and forth through the web page stack that is mapped to the browser back button.  So, if you intend to load the index_p0.html from 
the web browser the – Click to Return to the Index Page, will not work correctly and will take you beyond the index page.  If you double 
click the index page, the JavaScript buttons will work okay.

The only other issue that I noticed is that the unordered list bullets, on the index page are left justified if you use MS Edge and 
Chrome. 
