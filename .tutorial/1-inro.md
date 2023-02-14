# Introduction to HTML Elements

HTML, or HyperText Markup Language, is the standard markup language used to create web pages. In this chapter, we will cover the basics of HTML elements and how to create a simple HTML document.

## Basic HTML Structure

Every HTML document starts with a `<!DOCTYPE>` declaration, which tells the browser what version of HTML the document is using. This is followed by the `<html>` element, which contains the entire document.

```html
<!DOCTYPE html>
<html>
  <!-- Your HTML code here -->
</html>
```
The `<head>` element contains meta information about the document, such as the title and links to stylesheets and scripts.
```
<head>
  <title>My Webpage</title>
  <link rel="stylesheet" href="styles.css">
  <script src="script.js"></script>
</head>
```
The <body> element contains the main content of the document, such as headings, paragraphs, images, and links.

```
<body>
  <h1>Welcome to My Webpage</h1>
  <p>This is a paragraph of text.</p>
  <img src="image.jpg" alt="An image">
  <a href="https://example.com">Link to Example.com</a>
</body>
```

Creating a Simple HTML Document
To create a simple HTML document, start by creating a new text file and saving it with the .html file extension. Then, add the basic structure of an HTML document, along with some content in the <body> element.

```
<!DOCTYPE html>
<html>
  <head>
    <title>My Webpage</title>
  </head>
  <body>
    <h1>Welcome to My Webpage</h1>
    <p>This is a paragraph of text.</p>
    <img src="image.jpg" alt="An image">
    <a href="https://example.com">Link to Example.com</a>
  </body>
</html>
```