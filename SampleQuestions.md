### IF.03.01 Basic Web Techniques
# Reading Assignment 1: WWW and html

## Html
### 1. Name the components of html elements properly
Opening Tag: This is the first part of the HTML element and is enclosed in angle brackets. It indicates the start of an element. For example, &lt;tagname>.

Closing Tag: This is the second part of the HTML element and is also enclosed in angle brackets. It indicates the end of an element. For example, &lt;/tagname>.

Content: This is the actual content of the HTML element, such as text, images, or other elements. It is placed between the opening and closing tags. For example, &lt;tagname> Content &lt;/tagname>.

Attributes: These provide additional information about an element and are included within the opening tag. Attributes consist of a name and a value and are written as name-value pairs. For example, &lt;tagname attribute="value"> Content &lt;/tagname>.

### 2. Identify void elements and how they are denoted
Void elements in HTML are elements that do not have any content and do not require a closing tag. These elements are self-closing in nature. They are used to insert something into a web page, like an image or a line break, but do not contain any content of their own. Void elements do not have any closing tag.

### 3. Identify attributes
In HTML, attributes provide additional information about an element. They are always included in the opening tag of an element and are written as name-value pairs. Attributes can modify the behavior or appearance of an element, or provide additional functionality to it.

## 4. Write down the correct ``DOCTYPE`` declaration for html 5
&lt;!DOCTYPE html>

### 5. Write down syntactically correct statements for the following elements
   - Article (``<article>``)
   - Body (``<body>``)
   - line break (``<br/>``)
   - Headings (``<h1>``, ...)
   - Section with meta-information (``<head>``)
   - Top level element (``<html>``)
   - Image named ``Team.jpg`` (``<img src="Team.jpg">``)
   - Paragraph (``<p>``)
   - Section (``<section>``)
   - Label appearing in the title bar (``<title>``)
   - Link to other pages (``<a>``)
   - Comment (``<!-- This is a comment -->``)
   - Head with title and meta elements (``<head>``)

## Css
### 1. Name the components of a css rule properly
In CSS (Cascading Style Sheets), a rule consists of several components that define the styling for specific elements on a web page. The most important are: Selector, Declaration Block, Property, Value.

### 2. Use combinators properly: direct child, descendant, adjacent sibling, sibling
/* Direct Child Combinator */ <br>
div > p { <br>
    color: blue; <br>
}

/* Descendant Combinator */ <br>
div p {  <br>
    color: red;   <br>
}

/* Adjacent Sibling Combinator */ <br>
p + span {  <br>
    font-weight: bold;  <br>
}

/* General Sibling Combinator */ <br>
p ~ span {  <br>
    text-decoration: underline;  <br>
}

### 3. Specify colors by color names and in hexadecimal notation
Color Names: <br>
p { <br>
    color: red; /* Using a color name */ <br>
    background-color: blue; /* Using another color name */ <br>
}

Hexadecimal notation: <br>
p { <br>
    color: #FF0000; /* Red in hexadecimal notation */ <br>
    background-color: #0000FF; /* Blue in hexadecimal notation */ <br>
}

### 4. Declarations for color, background color
I answeres it above.

### 5. Pseudo classes for the ``<a>`` element
These are some common used pseudo classes for the ``<a>`` element: <br>
/* unvisited link */ <br>
a:link {
  color: blue;
}

/* visited link */ <br>
a:visited {
  color: purple;
}

/* mouse over link */ <br>
a:hover {
  color: red;
}

/* selected link */ <br>
a:active {
  color: green;
}

/* focused link */ <br>
a:focus {
  outline: 1px solid black;
}

/* target element */ <br>
a:target {
  background-color: yellow;
}

### 6. Declaration for background image
div {  <br>
  background-image: url('path_to_your_image.jpg'); <br>
}

### 7. Declaration for text alignment (left, right, center, justify)
p { <br>
    text-align: left; <br>
}

p { <br>
    text-align: right; <br>
}

p { <br>
    text-align: center; <br>
}

p { <br> 
    text-align: justify; <br>
}

### 8. Declaration for text decoration (overline, underline, line-through)
p {  <br>
    text-decoration: overline; <br>
}

p { <br>
    text-decoration: underline; <br>
}

p { <br>
    text-decoration: line-through; <br>
}

### 9. Declaration for text transformation (uppercase, lowercase, capitalize)
p { <br>
    text-transform: uppercase; <br>
}

p { <br> 
    text-transform: lowercase; <br>
}

p { <br>
    text-transform: capitalize; <br>
}

### 9. Identify the difference between serif and sans-serif fonts
Serif Fonts:

- Serif fonts have small lines or embellishments at the ends of the strokes of each letter.
- They are often considered more traditional and formal.
- Common examples of serif fonts include Times New Roman, Georgia, and Baskerville.

Sans-Serif Fonts:

- Sans-serif fonts, on the other hand, do not have these small lines or embellishments at the ends of the strokes.
- They are usually considered more modern and clean in appearance.
- Common examples of sans-serif fonts include Arial, Helvetica, and Calibri.

### 10. Declarations for font families
p { <br>
    font-family: Arial, sans-serif; <br>
}

h1 { <br>
    font-family: "Times New Roman", Times, serif; <br>
}

### 11. Declarations for font style normal and italic
p { <br>
    font-style: normal; <br>
}

em { <br>
    font-style: italic; <br>
}

### 12. Declarations for font sizes
p { <br>
    font-size: 16px; <br>
} <br>
The px (pixel) unit sets an absolute size for the font, where 1px is equal to 1/96th of 1 inch.

h1 { <br> 
    font-size: 2em; <br>
} <br>
The em unit sets the font size relative to the font size of the parent element. For example, 2em means the font size is twice the size of the parent element's font size.

h2 { <br>
    font-size: 1.5rem; <br>
} <br>
The rem unit sets the font size relative to the root element's font size. For example, 1.5rem means the font size is 1.5 times the root element's font size.

### 13. Declarations for font weights
p { <br>
    font-weight: normal; <br>
} <br>
The normal value sets the normal (regular) font weight. It is the default value for most fonts.

h1 { <br>
    font-weight: bold; <br>
} <br>
The bold value makes the text appear thicker and darker, indicating a stronger emphasis.

h2 { <br> 
    font-weight: 700; <br>
} <br>
The numeric values for font-weight range from 100 to 900, with 400 being the same as normal and 700 being the same as bold. Intermediate values represent different degrees of thickness.
