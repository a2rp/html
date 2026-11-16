# HTML: A Beginner's Guide



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

## Elements, tags, and attributes

An HTML element usually has an opening tag, content, and a closing tag:

    <p class="intro">Welcome to my page.</p>

- <p> is the opening tag.
- class="intro" is an attribute: extra information about the element.
- Welcome to my page. is the content.
- </p> is the closing tag.
- The opening tag, content, and closing tag together form the paragraph element.

Attribute values should usually be written in quotes. Some attributes are boolean: their presence turns an option on. For example, required on a form input means that a value must be provided before the form can be submitted.

Some elements are **void elements**. They cannot contain child content and do not use a closing tag. Common examples include <img>, <br>, <hr>, <meta>, <link>, <input>, and <source>.

## Text and headings

Use headings to organize a page. HTML provides six levels, from <h1> to <h6>. Start with a clear main heading, then use lower-level headings for sections in a sensible order.

Use <p> for paragraphs. Use <strong> when text is especially important and <em> when the emphasis should affect the meaning. Choose elements for what the content means, rather than for how you want it to look.

## Links and images

An anchor creates a link. Its href attribute gives the destination:

    <a href="about.html">About this page</a>

A link can point to another page, a section in the current page, or an external website. Use link text that describes the destination.

An image uses the src attribute for its file and the alt attribute for its text alternative:

    <img src="images/flower.jpg" alt="A yellow flower beside a garden path">

Write alt text that conveys the important information in the image. If an image is purely decorative and adds no information, use an empty alt value: alt="".

## Lists

Use an unordered list when the order does not matter:

    <ul>
      <li>Apples</li>
      <li>Oranges</li>
    </ul>

Use an ordered list when the sequence matters:

    <ol>
      <li>Open the file.</li>
      <li>Read the page.</li>
    </ol>

Each list item belongs inside an <li> element.

## Tables

Use a table for information that naturally belongs in rows and columns, such as a timetable. Do not use a table just to arrange the visual layout of a page.

A useful table has a caption and header cells so people can understand what its rows and columns represent:

    <table>
      <caption>Class timetable</caption>
      <thead>
        <tr>
          <th scope="col">Day</th>
          <th scope="col">Subject</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <th scope="row">Monday</th>
          <td>Science</td>
        </tr>
      </tbody>
    </table>

## Forms

Forms let people enter and submit information. Pair every input with a visible label:

    <form>
      <label for="email">Email address</label>
      <input id="email" name="email" type="email" required>
      <button type="submit">Send</button>
    </form>

The label's for value must match the input's id. The name identifies the value when a form is submitted. The type attribute selects an appropriate input, and required enables a built-in check that the field is not empty.

A form needs a destination and a receiving service to process submitted data. This example teaches the HTML structure; it does not send information to a server.

## Semantic page structure

Semantic elements describe the purpose of different parts of a page. Common examples include:

- <header> for introductory content or a page header.
- <nav> for a group of navigation links.
- <main> for the page's primary content.
- <article> for content that can stand on its own.
- <section> for a related, named group of content.
- <aside> for related supporting content.
- <footer> for information about a page or section.

Choose an element because it fits the content. Semantic structure helps browsers, assistive technologies, and other tools understand the page.

## Metadata and media

The <head> can include information about the document, including its title, language support, and a short description:

    <head>
      <meta charset="utf-8">
      <meta name="description" content="A beginner-friendly HTML guide">
      <title>HTML: A Beginner's Guide</title>
    </head>

HTML also provides elements for media. For example, <audio controls> and <video controls> give the browser's built-in media controls. Use captions for video when people need spoken content in text form.

## Accessibility basics

Accessible HTML makes pages easier for more people to use. Start with these habits:

- Set the document language with the lang attribute.
- Use headings in a meaningful order.
- Give informative images useful alt text.
- Connect form labels to their inputs.
- Use links whose text explains their destination.
- Use native HTML elements for their intended purposes.
- Provide table headers for data tables.
- Make controls understandable from their text and labels.

## Common beginner mistakes

- Leaving out the document title or language.
- Using headings only to make text appear prominent.
- Forgetting alt text or form labels.
- Using vague link text such as “click here.”
- Putting elements in an invalid or confusing nesting order.
- Reusing the same id value for multiple elements.
- Using tables to arrange page layout.
- Assuming a form sends data without a destination and a receiving service.

## Practice: make a profile page

Create index.html and build a small profile page that includes:

1. A document title and language.
2. One main heading and a short introduction.
3. A section with a list of interests.
4. A link to another page or website.
5. An image with an appropriate alt value.
6. A simple contact form with labels.

Open the page in your browser, then review the HTML and check that every element has a clear purpose.

## Keep practicing

Learn a few elements at a time, write them yourself, and check the result in a browser.

## License

This repository is licensed under the MIT License. See [LICENSE](LICENSE) for details.
