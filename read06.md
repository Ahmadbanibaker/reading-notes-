# What is CSS?
### CSS (Cascading Style Sheets) allows you to create great-looking web pages, but how does it work under the hood? This article explains what CSS is, with a simple syntax example, and also covers some key terms about the language.

## There are three ways of inserting a style sheet:
- External CSS
- Internal CSS
- Inline CSS

## 1. External CSS 
### With an external style sheet, you can change the look of an entire website by changing just one file!

### Each HTML page must include a reference to the external style sheet file inside the <link> element, inside the head section.

## 2. Internal CSS
### An internal style sheet may be used if one single HTML page has a unique style.

### The internal style is defined inside the <style> element, inside the head section.

## 3. Inline CSS
### An inline style may be used to apply a unique style for a single element.

### To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.

## CSS Tools: Reset CSS
### The goal of a reset stylesheet is to reduce browser inconsistencies in things like default line heights, margins and font sizes of headings, and so on. The general reasoning behind this was discussed in a May 2007 post, if you're interested. Reset styles quite often appear in CSS frameworks, and the original "meyerweb reset" found its way into Blueprint, among others.

### The reset styles given here are intentionally very generic. There isn't any default color or background set for the body element, for example. I don't particularly recommend that you just use this in its unaltered state in your own projects. It should be tweaked, edited, extended, and otherwise tuned to match your specific reset baseline. Fill in your preferred colors for the page, links, and so on.

### In other words, this is a starting point, not a self-contained black box of no-touchiness.

### If you want to use my reset styles, then feel free! It's all explicitly in the public domain (I have to formally say that or else people ask me about licensing). You can grab a copy of the file to use and tweak as fits you best. If you're more of the copy-and-paste type, or just want an in-page preview of what you'll be getting.

![CSS pic](https://miro.medium.com/max/600/1*qG3OT-9cER8Nt-P7KR3YPw.jpeg)