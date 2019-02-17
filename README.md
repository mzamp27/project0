# Project 0

Web Programming with Python and JavaScript


Alright, now it’s time to make your website your own. Design a personal webpage about yourself, one of your interests, or any other topic of your choice. The subject matter, look and feel, and design of the site are entirely up to you, subject to the following requirements:

    1.Your website must contain at least four different .html pages, and it should be possible to get from any page on your website to any other page by following one or more hyperlinks.
    2.Your website must include at least one list (ordered or unordered), at least one table, and at least one image.
    3.Your website must have at least one stylesheet file.
    Your stylesheet(s) must use at least five different CSS properties, and at least five different types of CSS selectors. You must use the #id selector at least once, and the .class selector at least once.
    4.Your stylesheet(s) must include at least one mobile-responsive @media query, such that something about the styling changes for smaller screens.
    5.You must use Bootstrap 4 on your website, taking advantage of at least one Bootstrap component, and using at least two Bootstrap columns for layout purposes using Bootstrap’s grid model.
    6.Your stylesheets must use at least one SCSS variable, at least one example of SCSS nesting, and at least one use of SCSS inheritance.
    In README.md, include a short writeup describing your project, what’s contained in each file, and (optionally) any other additional information the staff should know about your project.

Note that not all of the above requirements are covered in Lecture 0, some will be introduced in Lecture 1.


Project 0 overview:

My website consists of several pages to serve as a family fun project.  As I have 2 kids at home I decided to create 2 pages just for them along with a games page, and an interactive family tree page.  I've also included a shopping tab to serve as a potential Wishlist for Santa later on, but for now its just there to provide a table and as an experimentation page. (possibly for real world retail applications) I will now reference the provided checklist of requirements, explaining where each item was used in the website.

Item 1:  There are at least 4 webpages and it is possible to get from any page to any other page using the top navigation bar I've implemented in plain html and css.  

Item 2:  I've included an ordered list into the family tree page with 5 list items to include the generations of family members I know about.  The required table is included in the shopping page.  And multiple images are used throughout the website.

Item 3: On top of the bootstrap stylesheet I have at least 5 other stylesheets to format specific parts of the website.  The index.css stylesheet includes the styling for the page layout using an id #mainbody that I've attached to the main body. #Mainthomas is also on this css sheet to center and size the picture accordingly.  The h1 generic tag is used here to keep the header "Welcome to our website" maintained in size and orientation throughout the website(except for the experimental shopping page).  And lastly, but most important, is the following 3 selectors: #navcontainer, .horizontaltoolbar and a, are used to align and style my nav bar that is in all of the pages.  

Each page also has its own stylesheet for items specific to that page (again, except for shopping which I wanted to be completely in bootstrap). Michael's and Emilia's Favorite pics share a nearly identical css stylesheet which is used to control the color and layout of the page, as well as, sizing and styling for the pictures within each page.  Familytree.css contains styling specific to the ordered list that resides in the page along with an image selector because I was having rotational orientation problems with pictures taken off my computer. Games.css has styling for a canvas element which includes adjustments to the border, alignment and fill properties.  Hopefully the canvas will contain a small game in JavaScript I plan to write in the future.

Item 4:  I implemented 3 @media query responses in the index.css.  If the page is smaller than 600 pixels the background color becomes white and if you are on the main page, the Thomas the Train image is hidden just leaving the quote I wanted on the page now in black font instead of white).

Item 5:  I tried to mainly use bootstrap on the shopping page to get a sense for how it acted out alone, however, I did end up using it on Michaels Favorite Pics page to demonstrate the use of columns in Bootstrap's grid model.  I also ended up using it in familytree.html for its columns and grid alignment.  The first component I used was in the creation of a new nav bar.  I used an unordered list this time to contain list elements giving them the bootstrap code class="nav-item".  You can also see a couple bootstrap components I used in the creation of the table, class="table table-striped table-hover".  This code quickly styled the table in stripes and gave it a mouse hover styling.  Lastly, I included a button component (that currently does nothing) that says ADD TO CART and gave it a badge component that will be edited later on in JavaScript.

Item 6:  Lastly, for the SASS requirement I used it on the ordered and unordered lists in the familytree page.  Here I demonstrated the use of a variable for coloring male descendants in blue and female descendants in red.  Nesting is demonstrated by giving all the list items in an unordered list a disc, and alll list items in an ordered list a square.
Finally, inheritance is demonstrated by altering the background color of the ordered list items which I have given unique class names to.
