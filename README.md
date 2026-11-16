# HTML: A Beginner's Guide

## My links

[View my portfolio, profiles, contact, and support links](links.md)



## What is HTML?

HTML means **HyperText Markup Language**. It is the standard markup language used to describe the structure and meaning of content on the web.

HTML uses elements to identify content: a heading, a paragraph, a link, an image, a form, and so on. A browser reads the HTML document and presents that structure as a web page.

HTML is a markup language, not a programming language. This guide focuses on HTML itself: its document structure, elements, attributes, semantics, forms, media, and accessibility.

## What you need

You only need:

- A text editor.
- A web browser.
- A folder where you can save your files.

Create a file named index.html. Make sure the file ends in .html, then open it in your browser. When you edit and save it, refresh the browser to see the updated page.

## Your first HTML page

Copy this into index.html:

    <!doctype html>
    <html lang="en">
      <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <title>My first page</title>
      </head>
      <body>
        <h1>Hello, HTML!</h1>
        <p>This is my first web page.</p>
      </body>
    </html>

Save the file and open it in a browser. You should see a heading and a paragraph.

### What each part does

- <!doctype html> tells the browser to use modern HTML standards. It is a declaration, not an HTML element.
- <html lang="en"> is the root element. The lang attribute identifies the document's language.
- <head> contains document information, such as its title and character encoding.
- <meta charset="utf-8"> supports text from a wide range of languages and writing systems.
- <meta name="viewport" ...> provides information browsers use when displaying pages on small screens.
- <title> sets the page title shown in the browser tab.
- <body> contains the page content that people read and use.
- <h1> is the main heading.
- <p> is a paragraph.
- Indentation makes nested elements easier to read. Browsers do not require these exact spaces.
