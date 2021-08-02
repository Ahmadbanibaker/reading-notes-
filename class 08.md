# HTML & CSS Design and Build Websites JAVASCRIPT & JQUERY
## Chapter 15: Layout
* Normal flow 
position:static In normal flow, each block-level 
element sits on top of the next 
one. Since this is the default 
way in which browsers treat 
HTML elements, you do not 
need a CSS property to indicate 
that elements should appear 
in normal flow, but the syntax 
would be:
position: static; 
I have not specified a width
property for the heading 
element, so you can see how it 
stretches the width of the entire 
browser window by default.
* Relative Positioning 
position:relative  Relative positioning moves an 
element in relation to where it 
would have been in normal flow.
For example, you can move it 10 
pixels lower than it would have 
been in normal flow or 20% to 
the right.
You can indicate that an element 
should be relatively positioned 
using the position property 
with a value of relative.
* Absolute Positioning 
position:absolute When the position property 
is given a value of absolute, 
the box is taken out of normal 
flow and no longer affects the 
position of other elements on 
the page. (They act like it is not 
there.) 
The box offset properties (top
or bottom and left or right) 
specify where the element 
should appear in relation to its 
containing element.
* Fixed Positioning 
Fixed positioning is a type 
of absolute positioning that 
requires the position property 
to have a value of fixed.
It positions the element in 
relation to the browser window. 
Therefore, when a user scrolls 
down the page, it stays in the 
exact same place. It is a good 
idea to try this example in your 
browser to see the effect.
* Floating Elements 
The float property allows you 
to take an element in normal 
flow and place it as far to the 
left or right of the containing 
element as possible.
Anything else that sits inside 
the containing element will 
flow around the element that is 
floated.
* Clearing floats 
The clear property allows you 
to say that no element (within 
the same containing element) 
should touch the left or righthand sides of a box. It can take 
the following values:
left
The left-hand side of the box 
should not touch any other 
elements appearing in the same 
containing element.
right
The right-hand side of the 
box will not touch elements 
appearing in the same containing 
element.
both
Neither the left nor right-hand 
sides of the box will touch 
elements appearing in the same 
containing element.
none
Elements can touch either side.
![Possible Layouts:
960 Pixel wide
12 Column Grid](https://www.sitepoint.com/wp-content/uploads/2013/05/960-12-col-grid.jpg)
### Summary
* < div> elements are often used as containing elements 
to group together sections of a page.
* Browsers display pages in normal flow unless you 
specify relative, absolute, or fixed positioning.
* X The float property moves content to the left or right 
of the page and can be used to create multi-column 
layouts. (Floated items require a defined width.)
* Pages can be fixed width or liquid (stretchy) layouts.
* Designers keep pages within 960-1000 pixels wide, 
and indicate what the site is about within the top 600 
pixels (to demonstrate its relevance without scrolling).
* Grids help create professional and flexible designs.
* CSS Frameworks provide rules for common tasks.
* You can include multiple CSS files in one page.
