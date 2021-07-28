# HTML & CSS Design and Build Websites JAVASCRIPT & JQUERY
## Chapter 4: Links
* Writing Links
Links are created using the < a> element. Users can click on anything 
between the opening < a> tag and the closing < /a> tag. You specify 
which page you want to link to using the href attribute.
* Linking to Other Sites 
Links are created using the < a>
element which has an attribute 
called href. The value of the 
href attribute is the page that 
you want people to go to when 
they click on the link.
Users can click on anything that 
appears between the opening 
< a> tag and the closing < /a>
tag and will be taken to the page 
specified in the href attribute.
* Linking to Other Pages 
on the Same Site 
When you are linking to other 
pages within the same site, 
you do not need to specify the 
domain name in the URL. You 
can use a shorthand known as a 
relative URL.
* Email Links
mailto:To create a link that starts up 
the user's email program and 
addresses an email to a specified 
email address, you use the < a>
element. However, this time the 
value of the href attribute starts 
with mailto: and is followed by 
the email address you want the 
email to be sent to.
* Opening Links in
a New Window
target
If you want a link to open in a 
new window, you can use the 
target attribute on the opening 
< a> tag. The value of this 
attribute should be _blank.
* Linking to a Specific 
Part of the Same Page
At the top of a long page 
you might want to add a list 
of contents that links to the 
corresponding sections lower 
down. Or you might want to add 
a link from part way down the 
page back to the top of it to save 
users from having to scroll back 
to the top.
Before you can link to a specific 
part of a page, you need to 
identify the points in the page 
that the link will go to. You do 
this using the id attribute (which 
can be used on every HTML 
element). You can see that the 
< h1> and < h2> elements in this 
example have been given id
attributes that identify those 
sections of the page.
### Summary
* Links are created using the < a> element.
* The < a> element uses the href attribute to indicate 
the page you are linking to.
* X If you are linking to a page within your own site, it is 
best to use relative links rather than qualified URLs.
* You can create links to open email programs with an 
email address in the "to" field.
* You can use the id attribute to target elements within 
a page that can be linked to.

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

## Chapter 3 (first part): Functions, Methods, and Objects
### WHAT IS A FUNCTION?
Functions let you group a series of statements together to perform a 
specific task. If different parts of a script repeat the same task, you can 
reuse the function (rather than repeating the same set of statements). 
![function in js](https://s3.amazonaws.com/codecademy-content/courses/learn-javascript-functions/Diagram/declaration.svg)
### WHAT IS AN OBJECT?
Objects group together a set of variables and functions to create a model 
of a something you would recognize from the real world. In an object, 
variables and functions take on new names.
## 6 Reasons for Pair Programming 
1. Greater efficiency 
It is a common misconception that pair programming takes a lot longer and is less efficient. In reality, when two people focus on the same code base, it is easier to catch mistakes in the making. Research indicates that pair programing takes slightly longer, but produces higher-quality code that doesn’t require later effort in troubleshooting and debugging (let alone exposing users to a broken product).
2. Engaged collaboration 
When two programmers focus on the same code, the experience is more engaging and both programmers are more focused than if they were working alone. It is harder to procrastinate or get off track when someone else is relying on you to complete the work. Popping open your Facebook timeline is just that less enticing when someone else is looking at your screen.
3. Learning from fellow students
Everyone has a different approach to problem solving; working with a teammate can expose developers to techniques they otherwise would not have thought of. If one developer has a unique approach to a specific problem, pair programming exposes the other developer to a new solution.
4. Social skills
Pair programming is great for improving social skills. When working with someone who has a different coding style, communication is key. This can become more difficult when two programmers have different personalities.
5. Job interview readiness 
A common step in many interview processes involves pair programming between a current employee and an applicant, either in person or through a shared screen. They will carry out exercises together, such as code challenges, building a project or feature, or debugging an existing code base.
6. Work environment readiness 
Many companies that utilize pair programing expect to train fresh hires from CS-degree programs on how they operate to actually deliver a product. Code Fellows graduates who are already familiar with how pairing works can hit the ground running at a new job, with one less hurdle to overcome.





