# HTML & CSS Design and Build Websites JAVASCRIPT & JQUERY
## Chapter 7: Forms
* Why Forms?
The best known form on the web is probably
the search box that sits right in the middle of
Google's homepage.
* Form Controls
There are several types of form controls that
you can use to collect information from visitors
to your site.
ADDING TEXT: Text input (single-line)
Used for a single line of text such
as email addresses and names.Password input
Like a single line text box but it
masks the characters entered.
Making Choices:
Radio buttons
For use when a user must select
one of a number of options.Checkboxes
When a user can select and
unselect one or more options.
Submitting Forms:Submit buttons
To submit data from your form
to another web page.Image buttons
Similar to submit buttons but
they allow you to use an image
Uploading Files:
File upload
Allows users to upload files
(e.g. images) to a website.
* Form Structure
< form>
Form controls live inside a
< form> element. This element
should always carry the action
attribute and will usually have a
method and id attribute too.action
Every < form> element requires
an action attribute. Its value
is the URL for the page on the
server that will receive the
information in the form when it
is submitted.
method
Forms can be sent using one of
two methods: get or post.
* Text Input 
<input>
The <input> element is used
to create several different form
controls. The value of the type
attribute determines what kind
of input they will be creating.
type="text"
When the type attribute has a
value of text, it creates a singleline text input.
name
When users enter information
into a form, the server needs to
know which form control each
piece of data was entered into.
(For example, in a login form, the
server needs to know what has
been entered as the username
and what has been given as the
password.) Therefore, each form
control requires a name attribute.
The value of this attribute
identifies the form control and is
sent along with the information
they enter to the server.

* Password Input
<input>
type="password"
When the type attribute has
a value of password it creates
a text box that acts just like a
single-line text input, except
the characters are blocked out.
They are hidden in this way so
that if someone is looking over
the user's shoulder, they cannot
see sensitive data such as
passwords.
name
The name attribute indicates
the name of the password input,
which is sent to the server with
the password the user enters.

* Checkbox 
<input>
type="checkbox"
Checkboxes allow users to select
(and unselect) one or more
options in answer to a question.
name
The name attribute is sent to
the server with the value of the
option(s) the user selects. When
a question provides users with
options for answers in the form
of checkboxes, the value of the
name attribute should be the
same for all of the buttons that
answer that question.
value
The value attribute indicates
the value sent to the server if this
checkbox is checked.

### summary
* Whenever you want to collect information from
visitors you will need a form, which lives inside a
< form> element.
* Information from a form is sent in name/value pairs.
* X Each form control is given a name, and the text the
user types in or the values of the options they select
are sent to the server.
* X HTML5 introduces new form elements which make it
easier for visitors to fill in forms.

## Chapter 14: Lists, Tables & Forms
* Border on Empty Cells
If you have empty cells in
your table, then you can use
the empty-cells property to
specify whether or not their
borders should be shown.
Since browsers treat empty cells
in different ways, if you want to
explicitly show or hide borders
on any empty cells then you
should use this property.
It can take one of three values.
* Gaps Between Cells
The border-spacing property
allows you to control the
distance between adjacent cells.
By default, browsers often leave
a small gap between each table
cell, so if you want to increase
or decrease this space then
the border-spacing property
allows you to control the gap.
The value of this property is
usually specified in pixels. You
can specify two values if desired
to specify separate numbers for
horizontal and vertical spacing.
* Styling Submit Buttons
Here are some properties that
can be used to style submit
buttons. This example builds
on the one in the previous page,
and the submit button inherits
the styles set for the <input>
element on the last page.
color is used to change the
color of the text on the button.
text-shadow can give a 3D
look to the text in browsers that
support this property.
border-bottom has been used
to make the bottom border of
the button slightly thicker, which
gives it a more 3D feel.
* Styling Fieldsets
& Legends
Fieldsets are particularly helpful
in determining the edges of a
form. In a long form they can
help group together related
information within it.
The legend is used to indicate
what information is required in
the fieldset.
Properties commonly used with
these two elements include:
* Cursor Styles
The cursor property allows
you to control the type of mouse
cursor that should be displayed
to users.
For example, on a form you
might set the cursor to be a hand
when the user hovers over it.
Here are the most commonly
used values for this property.
### summary 
* X In addition to the CSS properties covered in other
chapters which work with the contents of all elements,
there are several others that are specifically used to
control the appearance of lists, tables, and forms.
* List markers can be given different appearances
using the list-style-type and list-style image
properties.
* Table cells can have different borders and spacing in
different browsers, but there are properties you can
use to control them and make them more consistent. 
* Forms are easier to use if the form controls are
vertically aligned using CSS.
* Forms benefit from styles that make them feel more
interactive.
## Chapter 6: Events
* HOW EVENTS TRIGGER
JAVASCRIPT CODE 
When the user interacts with the HTML on a web page, there are three
steps involved in getting it to trigger some JavaScript code.
Together these steps are known as event handling. 
* THREE WAYS TO BIND AN
EVENT TO AN ELEMENT
Event handlers let you indicate which event you
are waiting for on any particular element.
There are three types of event handlers. 
* USING DOM EVENT
HANDLERS
In this example, the event
handler appears on the last line
of the JavaScript. Before the
DOM event handler, two things
are put in place: 1. If you use a named function
when the event fires on your
chosen DOM node, write that
function first. (You could also
use an anonymous function.)2. The DOM element node is
stored in a variable. Here the text
input (whose id attribute has a
value of username) is placed into
a variable called e 1 Username.
* EVENT LISTENERS
Event listeners are a more recent approach to handling events.
They can deal with more than one function at a time
but they are not supported in older browsers. 
* USING PARAMETERS WITH
EVENT HANDLERS
& LISTENERS 
Because you cannot have parentheses after the
function names in event handlers or listeners,
passing arguments requires a workaround. 
* SUPPORTING OLDER
VERSIONS OF IE 
IES-8 had a different event model and did not support
addEventL i stener() but you can provide fallback code
to make event listeners work with older versions of IE. 
* THE EVENT OBJECT
When an event occurs, the event object tells
you information about the event, and the
element it happened upon. 
### summary
* Events are the browser's way of indicating when
something has happened (such as when a page has
finished loading or a button has been clicked). 
* Binding is the process of stating which event you are
waiting to happen, and which element you are waiting
for that event to happen upon. 
* When an event occurs on an element, it can trigger a
JavaScript function. When this function then changes
the web page in some way, it feels interactive because
it has responded to the user. 
* You can use event delegation to monitor for events
that happen on all of the children of an element. 
* The most commonly used events are W3C DOM
events, although there are others in the HTMLS
specification as well as browser-specific events.

