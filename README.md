LEARN SASS
============
Refactor CSS to SCSS
----------------------
The band at Common Cents Party wants to update their codebase by upgrading from old standard CSS— which is hard to maintain and ever-growing in complexity— to the more efficent and organized SCSS. 
Your first order of business is to help them refactor their code by nesting selectors and identifying variables. Let’s get started!

If you get stuck during this project or would like to see an experienced developer work through it, click “Get Unstuck“ to see a project walkthrough video.

1. Analyze the index.html and shows.html documents. The DOM relationships will help you decide how to nest your selectors. 
Take a look inside of style.scss, paste in the entire contents of style.css so we can begin refactoring.


Hint
Paste in the entire contents of style.css so we can begin refactoring.

2. Let’s start by defining variables to improve the readability of the codebase. At the top of the style.scss file, create a variable for every Hex value. 
Reference these variables where the Hex values used to appear.


Hint
Make two variables for both #ffffff and #FFCFCF

3. When first nesting selectors, it’s always best to start with the big picture. Look inside of shows.html and index.html. What is the outermost element in both files and what are its direct children? Start by nesting these selectors along with their properties in style.scss


Hint
Nest .nav and .main inside of .container.


4. Next, trickle down the DOM tree and focus solely on the .nav selector. What elements are direct children of this element? In style.scss, nest the selectors and their properties appropriately.


Hint
Nest the h4 and ul properties directly inside of .nav.

5. Let’s move down to the .main element. What elements are first descendants of .main? In style.scss, nest these selectors accordingly.


Hint
Inside of the .main selector, nest in h1,video, p, a and a:hover along with their properties.

6. Do any of first descendents of .nav or .main have descendents with properties? In style.scss, nest li and its properties inside of ul.


Hint
Nest li inside of ul which is inside of .main.


7. Let’s pause and recollect. Do you notice any value that repeats itself over and over again inside of .main?

If you look closely you will see that padding-left: 30px is an attribute of every direct child of .main.

There’s a shorthand CSS selector for applying a property to all direct children. Add the > * selector and define the property these elements have in common. Now that you’ve done this you can remove padding-left: 30px; everywhere else.


Hint
Include padding-left: 30px; inside of .main in style.scss.



SASS Project: Refractor CSS to SCSS
-------------------------------------
Youtube video link below

https://www.youtube.com/watch?v=b-vVirdguXI

codecademy lesson link below
-------------------------------

https://www.codecademy.com/courses/learn-sass/projects/refactor-scss-1
