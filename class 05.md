# HTML & CSS Design and Build Websites JAVASCRIPT & JQUERY
## Chapter 5: Images
* Adding Images 
< img> chapter-05/adding-images.html HTML
To add an image into the page
you need to use an < img>
element. This is an empty
element (which means there is
no closing tag). It must carry the
following two attributes:
src
This tells the browser where
it can find the image file. This
will usually be a relative URL
pointing to an image on your
own site. (Here you can see that
the images are in a child folder
called images — relative URLs
were covered on pages 83-84).
alt
This provides a text description
of the image which describes the
image if you cannot see it.
1: before a paragraph
The paragraph starts on a new
line after the image.
2: inside the start of a
paragraph
The first row of text aligns with
the bottom of the image.
3: in the middle of a
paragraph
The image is placed between the
words of the paragraph that it
appears in.
### Summary 
* The < img> element is used to add images to a
web page.

* You must always specify a src attribute to indicate the
source of an image and an alt attribute to describe the
content of an image.
* You should save images at the size you will be using
them on the web page and in the appropriate format.
* Photographs are best saved as JPEGs; illustrations or
logos that use flat colors are better saved as GIFs.
## Chapter 11: Color
* background-color 
CSS treats each HTML element
as if it appears in a box, and the
background-color property
sets the color of the background
for that box.
You can specify your choice of
background color in the same
three ways you can specify
foreground colors: RGB values,
hex codes, and color names
(covered on the next page).
* CSS3: HSL Colors 
CSS3 introduces an entirely new and intuitive
way to specify colors using hue, saturation,
and lightness values.
* hsl, hsla 
The hsl color property has
been introduced in CSS3 as an
alternative way to specify colors.
The value of the property starts
with the letters hsl, followed
by individual values inside
parentheses for:
hue
This is expressed as an angle
(between 0 and 360 degrees).
saturation
This is expressed as a
percentage.
lightness
This is expressed as a
percentage with 0% being white,
50% being normal, and 100%
being black.
### Summary 
* Color not only brings your site to life, but also helps
convey the mood and evokes reactions.
* There are three ways to specify colors in CSS:
RGB values, hex codes, and color names.
* Color pickers can help you find the color you want.
* It is important to ensure that there is enough contrast
between any text and the background color (otherwise
people will not be able to read your content).
* CSS3 has introduced an extra value for RGB colors to
indicate opacity. It is known as RGBA.
* CSS3 also allows you to specify colors as HSL values,
with an optional opacity value. It is known as HSLA.
## Chapter 12: Text
* font-weight 
The font-weight property
allows you to create bold text.
There are two values that this
property commonly takes:
normal
This causes text to appear at a
normal weight.
bold
This causes text to appear bold.
* font-style
If you want to create italic text,
you can use the font-style
property. There are three values
this property can take:
normal
This causes text to appear in a
normal style (as opposed to italic
or oblique).
italic
This causes text to appear italic.
oblique
This causes text to appear
oblique.
* text-transform 
The text-transform property
is used to change the case of
text giving it one of the following
values:
uppercase
This causes the text to appear
uppercase.
lowercase
This causes the text to appear
lowercase.
capitalize
This causes the first letter of
each word to appear capitalized.
* text-decoration 
The text-decoration property
allows you to specify the
following values:
none
This removes any decoration
already applied to the text.
underline
This adds a line underneath the
text.
overline
This adds a line over the top of
the text.
line-through
This adds a line through words.
blink
This animates the text to make it
flash on and off (however this is
generally frowned upon, as it is
considered rather annoying).
* text-align 
The text-align property allows
you to control the alignment of
text. The property can take one
of four values:
left
This indicates that the text
should be left-aligned.
right
This indicates that the text
should be right-aligned.
center
This allows you to center text.
justify
This indicates that every line in
a paragraph, except the last line,
should be set to take up the full
width of the containing box.
![text in css](https://cdn.educba.com/academy/wp-content/uploads/2019/08/CSS-Text-Formatting-Properties2.png)
- JPEG images don’t support transparency and are hence not usable for such cases.
- PNG images support transparency in two ways — inserting an alpha channel that allows partial transparency or by declaring a single colour as transparent (index transparency). Partial transparency makes the edges blend smoothly into the background. PNG8 images (discussed in the “Colours” section below) can support only index transparency whereas PNG24 images can support alpha channel transparency.
- GIF images support transparency by declaring a single colour in the colour palette as transparent (index transparency). Because of absence of partial transparency, the edges (specially rounded or too-detailed edges) get a poor jagged effect. Though this can be solved to some extent using dithering, with improved PNG support, GIF is unsuitable for images with transparent backgrounds.