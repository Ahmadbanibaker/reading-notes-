# HTML & CSS Design and Build Websites JAVASCRIPT & JQUERY
## chapter 2 : Text 
* ## Headings 
![headings](https://programmingbasics.in/contents/languages/html/images/headings.jpg)

## Paragraphs
To create a paragraph, surround 
the words that make up the 
paragraph with an opening 
tag and closing  tag.
By default, a browser will show 
each paragraph on a new line 
with some space between it and 
any subsequent paragraphs.

* Bold : By enclosing words in the tags 
<b> and </b> we can make 
characters appear bold .
* Italic : By enclosing words in the tags 
<i> and </i> we can make 
characters appear italic.
* sup : The <sup> element is used 
to contain characters that 
should be superscript such 
as the suffixes of dates or 
mathematical concepts like 
raising a number to a power.
* sub : The <sub> element is used to 
contain characters that should 
be subscript. It is commonly 
used with foot notes or chemical 
formulas.
* Line Breaks : < br /
As you have already seen, the 
browser will automatically show 
each new paragraph or heading 
on a new line. But if you wanted 
to add a line break inside the 
middle of a paragraph you can 
use the line break tag < br /.
* Horizontal Rules : < hr />
To create a break between 
themes — such as a change of 
topic in a book or a new scene 
in a play — you can add a 
horizontal rule between sections 
using the < hr /> tag.
* Strong : The use of the <strong>
element indicates that its 
content has strong importance. 
For example, the words 
contained in this element might 
be said with strong emphasis.
By default, browsers will show 
the contents of a < strong>
element in bold.
## Quotations
* blockquote : The < blockquote> element is 
used for longer quotes that take 
up an entire paragraph. Note 
how the < p> element is still 
used inside the < blockquote>
element. 
Browsers tend to indent the 
contents of the < blockquote>
element, however you should not 
use this element just to indent a 
piece of text — rather you should 
achieve this effect using CSS. 
* Abbreviations & 
Acronyms :If you use an abbreviation or 
an acronym, then the < abbr>
element can be used. A title
attribute on the opening tag is 
used to specify the full term.
* Citations : When you are referencing a 
piece of work such as a book, 
film or research paper, the 
< cite> element can be used 
to indicate where the citation is 
from.
In HTML5, < cite> should not 
really be used for a person's 
name — but it was allowed in 
HTML 4, so most people are 
likely to continue to use it.
* Definitions : The first time you explain some 
new terminology (perhaps an 
academic concept or some 
jargon) in a document, it is 
known as the defining instance 
of it.
The < dfn> element is used to 
indicate the defining instance of 
a new term.
* Author Details : The <address> element has 
quite a specific use: to contain 
contact details for the author of 
the page.
It can contain a physical address, 
but it does not have to. For 
example, it may also contain a 
phone number or email address.

## chapter 10 : Introducing CSS
'The key to understanding how CSS works is to 
imagine that there is an invisible box around 
every HTML element.'

![css style](https://images.slideplayer.com/32/9811421/slides/slide_5.jpg)
## Using External CSS
* The < link> element can be used 
in an HTML document to tell the 
browser where to find the CSS 
file used to style the page. It is an 
empty element (meaning it does 
not need a closing tag), and it 
lives inside the < head> element. 
It should use three attributes:
href
This specifies the path to the 
CSS file (which is often placed in 
a folder called css or styles).
type
This attribute specifies the type 
of document being linked to. The 
value should be text/css.rel
This specifies the relationship 
between the HTML page and 
the file it is linked to. The value 
should be stylesheet when 
linking to a CSS file.
## Using Internal CSS
* You can also include CSS rules 
within an HTML page by placing 
them inside a < style> element, 
which usually sits inside the 
< head> element of the page. 
The < style> element should use 
the type attribute to indicate 
that the styles are specified in 
CSS. The value should be text/
css.
## CSS Selectors 
* There are many different types 
of CSS selector that allow you to 
target rules to specific elements 
in an HTML document. 
The table on the opposite page 
introduces the most commonly 
used CSS selectors.
On this page, there is an HTML 
file to demonstrate which 
elements these CSS selectors 
would apply to.
### Summary
* CSS treats each HTML element as if it appears inside 
its own box and uses rules to indicate how that 
element should look.
* Rules are made up of selectors (that specify the 
elements the rule applies to) and declarations (that 
indicate what these elements should look like).
* Different types of selectors allow you to target your 
rules at different elements.
* Declarations are made up of two parts: the properties 
of the element that you want to change, and the values 
of those properties. For example, the font-family 
property sets the choice of font, and the value arial 
specifies Arial as the preferred typeface.
* CSS rules usually appear in a separate document, 
although they may appear within an HTML page.

## Chapter 2: Basic JavaScript Instructions
- A script is a series of instructions that a computer can follow one-by-one. 
Each individual instruction or step is known as a statement. 
Statements should end with a semicolon.
* You should write comments to explain what your code does. 
They help make your code easier to read and understand. 
This can help you and others who read your code. 
* A script will have to temporarily 
store the bits of information it 
needs to do its job. It can store this 
data in variables. A variable is a good name for this 
concept because the data stored 
in a variable can change (or vary) 
each time a script runs.
![var ](https://1.bp.blogspot.com/-8UmWFTngfwY/XkVRuoPFfkI/AAAAAAAACmI/93j-FMkA9EYyoRIT1qlJ2sMUbobnWT1UgCLcBGAsYHQ/s1600/javascript_var.png)
### DATA TYPES : 
1. NUMERIC DATA : The numeric data type handles 
numbers.
2. STRING DATA : The strings data type consists of 
letters and other characters.
3. BOOLEAN DATA : Boolean data types can have one 
of two values: true or false. 
## Chapter 4: Decisions and Loops
![loops](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/07/JavaScript-Loops-1200x720.jpg)
### USING IF STATEMENTS
* In this example, the i f statement 
is checking if the value currently 
held in a variable called score is 
50 or more. 
In this case, the statement 
evaluates to true (because the 
score is 75, which is greater than 
50). Therefore, the contents 
of the statements within the 
subsequent code block are 
run, creating a message that 
congratulates the user and tells 
them to proceed. 
After the code block, the 
message is written to the page. 
![if statement ](https://miro.medium.com/max/2400/1*VkY6u7wuucQ_4e6iZl-qxw.png)


![for loop ](https://slidetodoc.com/presentation_image/13d91d3fac1401181032f75724d23b47/image-42.jpg)











