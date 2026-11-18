# 01 - Introduction to HTML: Questions and Answers

Practice questions for [Lesson 01 - Introduction to HTML](../lessons/01-introduction-to-html.md). Try the questions before checking the answers at the end.

## Multiple-choice questions

Choose one answer for each question.

1. What does HTML stand for?
   - A. HyperText Markup Language
   - B. HighText Machine Language
   - C. Hyperlink and Text Management Language
   - D. Home Tool Markup Language

2. What is HTML mainly used for?
   - A. Choosing the colors and spacing of a page
   - B. Describing the structure and meaning of page content
   - C. Running calculations in a browser
   - D. Storing files on a server

3. Which technology is mainly used for presentation and layout?
   - A. HTML
   - B. CSS
   - C. JavaScript
   - D. A web browser

4. Which technology can add behavior and logic to a page?
   - A. HTML
   - B. CSS
   - C. JavaScript
   - D. A file extension

5. In `<a href="https://example.com/">Visit Example</a>`, what does `href` provide?
   - A. The link's destination
   - B. The page title
   - C. The link's font
   - D. The browser name

6. Which choice describes an HTML element?
   - A. Only the text between angle brackets
   - B. The complete structure made from tags and, where applicable, content
   - C. A browser window
   - D. A CSS color

7. Which element is a void element and does not have an end tag?
   - A. `<p>`
   - B. `<strong>`
   - C. `<img>`
   - D. `<h1>`

8. What does a browser do with an HTML document?
   - A. Parses it and builds a structured representation of the page
   - B. Automatically writes CSS for every element
   - C. Converts every link into JavaScript
   - D. Changes the source file into a word-processing document

9. Where does the main page content belong in a basic document?
   - A. Inside `<title>`
   - B. Inside `<body>`
   - C. Inside `<meta>`
   - D. Before the doctype

10. Which is the best element for the main visible heading in the chapter's example?
    - A. `<title>`
    - B. `<meta>`
    - C. `<h1>`
    - D. `<html>`

## Objective questions

### True or false

1. HTML stands for HyperText Markup Language.
2. CSS is mainly responsible for the structure and meaning of content.
3. A page can contain useful HTML even when it has no CSS or JavaScript.
4. The browser parses HTML and uses it to build a structured representation.
5. The text `class="intro"` in `<p class="intro">` is an attribute.
6. A tag and an element mean exactly the same thing.
7. Every HTML element has an end tag.
8. The `<title>` is commonly shown in the browser tab.
9. The `href` attribute holds the destination of a link.
10. The `<strong>` element communicates strong importance, even if a browser often displays it in bold.

### Fill in the blanks

1. HTML means ______________________________.
2. The technology commonly used for colors, fonts, and layout is __________________.
3. The attribute that gives an anchor element its destination is __________________.
4. The main page content belongs inside the __________________ element.
5. An element that does not have an end tag, such as `<img>`, is called a __________________ element.

## Short-answer questions

Answer in one or a few sentences.

1. Explain the difference between HTML, CSS, and JavaScript.
2. What is the difference between an HTML source file and the rendered page?
3. In `<p class="intro">I am learning HTML.</p>`, identify the start tag, attribute, content, end tag, and complete element.
4. Why should you choose an HTML element for the meaning of the content instead of only for its default appearance?
5. Why can a link work without JavaScript?

## HTML practice questions

### 1. Build a simple page

Create a complete HTML document about a hobby. It must include:

- A doctype and an `html` root element with a language attribute
- A head with a character encoding and a page title
- A body with one main heading and two paragraphs

### 2. Add a useful link

Add a link to an HTML learning resource. The link must have a destination and descriptive text that makes sense when read by itself.

### 3. Repair the markup

The following page has several problems. Rewrite it as a clear, complete HTML document.

~~~html
<html>
<head>
  <h1>About me</h1>
  <title>About me</title>
</head>
<body>
  <p>I am learning HTML.</p>
  <a>My HTML learning resource</a>
</body>
</html>
~~~

## Answers

### Multiple-choice answers

1. A. HyperText Markup Language
2. B. Describing the structure and meaning of page content
3. B. CSS
4. C. JavaScript
5. A. The link's destination
6. B. The complete structure made from tags and, where applicable, content
7. C. `<img>`
8. A. It parses the document and builds a structured representation of the page
9. B. Inside `<body>`
10. C. `<h1>`

### True or false answers

1. True
2. False. CSS mainly controls presentation and layout.
3. True
4. True
5. True
6. False. Tags are markup. An element is the complete structure made from tags and content, where applicable.
7. False. Void elements such as `<img>` do not have end tags.
8. True
9. True
10. True

### Fill-in-the-blank answers

1. HyperText Markup Language
2. CSS
3. `href`
4. `body`
5. Void

### Short-answer examples

1. HTML describes page structure and meaning. CSS controls presentation and layout. JavaScript can add behavior and logic.
2. The source file is the HTML markup written by the author. The rendered page is the result the browser displays after it interprets that markup.
3. Start tag: `<p class="intro">`. Attribute: `class="intro"`. Content: `I am learning HTML.`. End tag: `</p>`. The complete element includes the start tag, content, and end tag.
4. Choosing an element for meaning gives the content a useful structure. Its appearance can be changed separately, while its meaning remains clear to browsers and assistive technologies.
5. An anchor element with an `href` has a destination that the browser can navigate to. JavaScript is not required for ordinary link navigation.

### HTML practice answers

#### 1. Example page

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>My Favorite Hobby</title>
</head>
<body>
  <h1>My Favorite Hobby</h1>
  <p>I enjoy drawing in my free time.</p>
  <p>Practicing regularly helps me learn new techniques.</p>
</body>
</html>
~~~

Other correct answers can use a different hobby and wording, as long as the document has the requested structure.

#### 2. Example link

~~~html
<a href="https://developer.mozilla.org/en-US/docs/Web/HTML">HTML documentation on MDN</a>
~~~

The `href` attribute gives the destination, and the link text describes what the reader will find.

#### 3. Repaired page

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>About me</title>
</head>
<body>
  <h1>About me</h1>
  <p>I am learning HTML.</p>
  <a href="https://developer.mozilla.org/en-US/docs/Web/HTML">My HTML learning resource</a>
</body>
</html>
~~~

The repaired version adds a doctype, language, and character encoding. It moves the heading into the body and gives the link an `href` destination.

---

### Chapter navigation

| Previous chapter | Next chapter |
| --- | --- |
|  | [02 - How HTML fits into a web page](02-html-css-and-javascript.md) |
