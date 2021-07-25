# Mortgage Calculator: Code Louisville Front End Final Project July 2021

## Purpose

This page was built to help potential home buyers understand some of the costs associated with taking and repaying a mortgage. This site can be viewed at https://tosha-g.github.io/codelouisville/ or by cloning the repository. 

## Project requirements and features

1. **2 media queries and a mobile-first perspective** - There are two breakpoints (759 and 1024 min-width). On a mobile layout, each section is stacked vertically in a column and the main navigation menu is also vertically aligned. At the first breakpoint, the main navigation changes to a horizontal arrangement and the content on the page changes to an inverted pyramid layout. At the next breakpoint, all content in the boxes changes to double spacing and the box sections are spaced out wider to make better use of the white space (and assist users with fine motor difficulties)
2. **CSS features** -   
+ This index page has a main navigation menu that begins in a vertical layout for smaller devices and realigns to a horizontal layout for larger devices
+ This project used Flexbox to create a responsive layout with container that held multiple items, such as image icons, buttons, and a expandable detail section with multiple columns. Additionally, when switching from mobile to medium-sized screens, the layout of the page switches from a single column to a two-column layout.
+  The main navigation button have a transition animation upon hover that highlights and expands the box being moused over while changing the color of the text.
3. **JavaScript features** - 
+ This page is one form with two fieldsets. Based upon the numbers input by the user, a calculation is performed and the answer is displayed on the page. The first function is a simple arithmetic (subtraction and percents) function. The bottom function uses the PMT function for interest that compounds monthly to estimate the monthly payment needed based on the loan amount taken, as well as the total amount and interest that will be paid once the loan is fully paid back.
+ The new home page uses an array (of image links) and the Math.floor and Math.random functions multipled by the length of the arry to generate a random image of a home when the button is clicked.

I would like to thank the mentors for their guidance and volunteering so much of their time. They were so helpful and accessible. 
Finally, in the "About Us" section, there is a dedication to my wonderful support system, without whom this project would not have been possible. 
