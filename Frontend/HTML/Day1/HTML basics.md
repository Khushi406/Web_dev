# Que1: What is HTML?
HTML stands for HyperText Markup Language.
It’s the standard language used to create web pages.
HTML is used to structure content — like text, images, videos, and links — on a webpage.

# Basic Structure of a Webpage:
  ` <!DOCTYPE html>
<html>
  <head>
    <title>My First Webpage</title>
  </head>
  <body>
    <h1>Hello World!</h1>
    <p>This is my first webpage using HTML.</p>
  </body>
</html>`


 Tag	                     Purpose
1. `<!DOCTYPE html>`:	Tells the browser that this is an HTML5 document.
2. `<html>`:	Root of the document. Everything goes inside this.
3. `<head>`:	Meta-information (like title, links to CSS/JS, etc.). Doesn’t display directly on the page.
4. `<title>`:	Sets the title of the browser tab.
5. `<body>`:	Actual content visible on the page (text, images, buttons, etc.).


#  Important Basic Tags
## Headings 
     <h1>This is heading 1</h1>
     <h2>This is heading 2</h2>
     ...
     <h6>This is heading 6</h6>

* h1 is the largest heading.
* h6 is the smallest.

## Paragraph
      <p>This is a paragraph of text.</p>

## Link
      <a href="https://www.google.com">Visit Google</a>

* href is the attribute that holds the URL.

## Image
      <img src="image.jpg" alt="A beautiful view">

* src = image path 
* alt = description (shown if image doesn’t load)      

##  Line Break
      Line 1<br>
      Line 2

## Horizontal Line
      <hr>


#  Nesting Tags
   You can place tags inside other tags.
      <p>This is a <strong>bold</strong> word inside a paragraph.</p>
* <strong> is nested inside <p>.   
* Always close the inner tags before outer tags.


# HTML Comments
      <!-- This is a comment -->
* Comments don’t show up in the browser.
* Used to explain or organize code.



# Quetions:
1. What is the purpose of the `<!DOCTYPE html>` declaration?
(Why is it used and where is it placed?)
2. What’s the difference between `<head>` and `<body>` tags in HTML?
3. Can you explain the importance of the alt attribute in an `<img>` tag?
4. What happens if we forget to close an HTML tag, like `<p>` or `<a>`?
5. What is semantic HTML? Can you name some semantic tags?
6. What’s the difference between `<h1>` and `<h6>`?
7. How many times should `<h1>` be used on a page and why?
8. Why is the alt attribute important in `<img>`?
9. How do you make a link open in a new browser tab?
10. Can you add a link to an image in HTML?