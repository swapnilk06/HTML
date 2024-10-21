# HTML In Shorts</br>
  - ### 1] Start of HTML
  - ### 2] Emmit
  - ### 3] Common HTML Tags
<br>

## 1] Start of HTML :

### What is HTML? </br>
HTML stands for HyperText Markup Language. It is a markup language used to create web pages. It is used to define the structure of a web page, including the content, layout, and style.

### What is HTML5? </br>
- HTML5 is a version of HTML that is designed to be backwards compatible with older versions of HTML. It includes new features and improvements that make it easier to create and maintain web pages. 
- In short, some new tags and attributes are added to HTML5 to make it more user-friendly and easier to use.

### How much HTML do I need to know? </br>
- You just need to know the basics of HTML. 
- You should not spend more than a weekend to learn HTML. Just get the basics done and you will be good to go.


### Text/code Editor vs Word processor </br>
- Text editors are used to write and edit text files. Specially code editors comes with features like syntax highlighting, auto-completion, and code formatting.
- Word processors are used to create and edit documents. They are used to create documents like books, reports, and presentations.


### Recommended code editor extensions
- HTML Snippets
- Live Server

### EMMIT HTML
- To create a new HTML file, open a text editor and create a new file with the <mark>.html</mark> extension.
- Emmit is used to produce code faster with shortcuts. No one nowadays writes HTML code by hand. Emmit takes care of it for you.

<br>

## 2] Emmit :
- Emmit is a code snippets manager for VS Code. It is used to create HTML code faster.
- Emmit is a must-have tool for any web developer.
- In VS Code, Emmit is enabled by default. It works only after you have created a new HTML file.

|| _Learn the shortcuts and just press the <mark>tab</mark> or <mark>enter key</mark> to get the code you want._

### Some common Emmit shortcuts
```
! - Inserts a <!DOCTYPE html> tag
h1 - Inserts a <h1> tag
h2 - Inserts a <h2> tag
p - Inserts a <p> tag
img - Inserts an <img> tag
a - Inserts an <a> tag
ul - Inserts an <ul> tag
ul>li - Inserts a <li> tag inside an <ul> tag
ul>li>a - Inserts an <a> tag inside a <li> tag inside an <ul> tag
ul>li*3 - Inserts 3 <li> tags inside an <ul> tag
div - Inserts a <div> tag
div>p - Inserts a <p> tag inside a <div> tag
div>p*3 - Inserts 3 <p> tags inside a <div> tag
```


### Some common Emmit shortcuts
```
# - Inserts an id attribute
. - Inserts a class attribute
```
Example:
- #my-id - Inserts an id attribute with the value my-id
- .my-class - Inserts a class attribute with the value my-class


### Grouping <br>
```
- div>(header>ul>li*2>a)+footer>p
- Inserts a <div> tag with a <header> tag inside it, a <ul> tag inside it, and 2 <li> tags inside the <ul> tag.
- Then it inserts an <a> tag inside each <li> tag. Finally it inserts a <footer> tag and a <p> tag inside it.
```

### CSS shortcuts <br> 
- style - Inserts a <style> tag
- pos - Inserts a position property
- pos:absolute - Inserts a position property with the value absolute
- bgc - Inserts a background-color property
- bgc:red - Inserts a background-color property with the value red
- ma - Inserts a margin:auto property


### Conclusion
Emmit is a must-have tool for any web developer. BUT this does not mean you have to learn every single shortcut. You can use Emmit to create HTML code faster. NO ONE remembers all the shortcuts. We use then mostly by trial and error, and learning them as we go.

<br>

## 3] Common HTML tags :

### Enough of HTML that you need to know </br>
HTML5 just adds a few new tags and attributes to HTML. Of course accessibility is a really long topic to be discussed but we will not be discussing it here. Accessibility is something that you will learn later, specially if you are planning to work on a web application with javascript or js frameworks.

### Basic terminology </br>
- Tag - A tag is a piece of text that is enclosed in angle brackets. It is used to define the structure of an HTML document.
- Attribute - An attribute is a piece of text that is placed inside the opening tag of an HTML element. It is used to provide additional information about the element.
- Element - An element is a piece of text that is enclosed in angle brackets and can have attributes. It is used to define the content of an HTML document.

### HTML tags for text <br>
```
<p> - Paragraph
<span> - Span
<div> - Div
<a> - Anchor
<img> - Image
<br> - Break
<hr> - Horizontal rule
<b> - Bold
<i> - Italic
<u> - Underline
<strong> - Strong
<em> - Emphasis
<code> - Code
<pre> - Preformatted text
```

### HTML tags for lists <br>
```
<ul> - Unordered list
<ol> - Ordered list
<li> - List item
```

### HTML tags for tables <br>
```
<table> - Table
<tr> - Table row
<td> - Table cell
```

### HTML tags for forms <br>
```
<form> - Form
<input> - Input field
<textarea> - Text area
<select> - Select box
<option> - Option
<button> - Button
```

### HTML tags for images <br>
```
<img> - Image
<source> - Source
<picture> - Picture
<video> - Video
```

### HTML tags for links <br>
```
<link> - Link
<meta> - Meta
<link rel="stylesheet"> - Stylesheet
<link rel="icon"> - Icon
```

### HTML tags for scripts <br>
```
<script> - Script
<script src="script.js"></script> - Script with src
<script async src="script.js"></script> - Script with async and src
<script defer src="script.js"></script> - Script with defer and src
<script type="module" src="script.js"></script> - Script with type module and src
```

### HTML tags for meta tags <br>
```
<meta charset="utf-8"> - Charset
<meta name="viewport" content="width=device-width, initial-scale=1.0"> - Viewport
<meta name="description" content="Description"> - Description
<meta name="author" content="Author"> - Author
<meta name="keywords" content="Keywords"> - Keywords
<meta name="robots" content="index, follow"> - Robots
<meta name="googlebot" content="index, follow"> - Googlebot
```

### HTML tags for media <br>
```
<audio> - Audio
<video> - Video
<source> - Source
<track> - Track
<iframe> - Iframe
<embed> - Embed
<object> - Object
```


### Attributes for HTML tags <br>

#### Attributes examples
```
<p id="my-id" class="my-class">Hello world</p>
<img src="image.jpg" alt="Image">
<a href="https://www.google.com">Google</a>
<input type="text" placeholder="Enter your name">
<button>Click me</button>
```
```
id="my-id" - Adds an id attribute with the value my-id
.my-class - Adds a class attribute with the value my-class
src="image.jpg" - Adds a src attribute with the value image.jpg
alt="Image" - Adds an alt attribute with the value Image
href="https://www.google.com" - Adds a href attribute with the value https://www.google.com
type="text" - Adds a type attribute with the value text
placeholder="Enter your name" - Adds a placeholder attribute with the value Enter your name
```

- Some attributes are global attributes and can be used on any HTML tag. Some attributes are specific to certain tags and can only be used with that tag. For example, the href attribute is a specific attribute for the <a> tag, and the title attribute is a global attribute that can be used on any HTML tag.

### HTML5 attributes <br>

Some examples of HTML5 attributes are:
```
autofocus - Adds an autofocus attribute to an input field
required - Adds a required attribute to an input field
readonly - Adds a readonly attribute to an input field
section - Adds a section attribute to a section element
footer - Adds a footer attribute to a footer element
```

- footer, section, and header are new HTML5 attributes. They are used to define the structure of a web page. Fundamentally, they are used to group related content together, just like the <div> tag is used to group related content together.

### HTML5 tags
```
<header> - Header
<footer> - Footer
<nav> - Navigation
<main> - Main
<article> - Article
<section> - Section
<aside> - Aside
<details> - Details
<summary> - Summary
<time> - Time
<mark> - Mark
<meter> - Meter
<progress> - Progress
<video> - Video
<audio> - Audio
<source> - Source
Conclusion
```

### Conclusion <br>
You don’t need to do a PhD in HTML to be a web developer. You just need to know the basics and get out of here ASAP. HTML5 just adds a few new tags and attributes to HTML. Rest all the stuff like Web APIs (local storage, session storage, etc.) are just JavaScript stuff. 
