# Example 38 - Header, navigation, main, section, article, and footer

## Question

How can the major regions of an article page be organized?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Header, navigation, main, section, article, and footer</title>
</head>
<body>
  <header>
    <p>Field Notes</p>
    <nav aria-label="Main navigation">
      <a href="#article">Article</a>
      <a href="#about">About</a>
    </nav>
  </header>
  <main>
    <article id="article">
      <header><h1>Planting a small herb garden</h1></header>
      <section>
        <h2>Choose a location</h2>
        <p>Find a place with suitable light.</p>
      </section>
      <footer><p>Written for new gardeners.</p></footer>
    </article>
  </main>
  <footer id="about"><p>About Field Notes</p></footer>
</body>
</html>
~~~

## Expected output

The page shows a header with navigation, a main article with a section, and footer information.

## Explanation

header and footer describe introductory and closing regions. nav identifies navigation, main marks the dominant page content, article marks a self-contained composition, and section groups related content.

## Related lesson

[Read the lesson](../lessons/38-page-structure-elements.md)
