# Example 54 - HTML-only practice pages

## Question

How can you combine headings, links, lists, and sections in a small HTML-only page?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>HTML-only practice pages</title>
</head>
<body>
  <header>
    <h1>My garden journal</h1>
    <nav aria-label="Main navigation">
      <a href="#plants">Plants</a>
      <a href="#notes">Notes</a>
    </nav>
  </header>
  <main>
    <section id="plants">
      <h2>Plants I am growing</h2>
      <ul>
        <li>Basil</li>
        <li>Tomato</li>
      </ul>
    </section>
    <section id="notes">
      <h2>Today's note</h2>
      <p>The seedlings need a little more sunlight.</p>
    </section>
  </main>
  <footer><p>Garden journal practice page</p></footer>
</body>
</html>
~~~

## Expected output

A small journal page appears with a header, navigation links, two content sections, a list, and a footer.

## Explanation

This practice page combines native HTML elements into a complete document. The links move to sections on the same page, and the content remains understandable without CSS or JavaScript.

## Related lesson

[Read the lesson](../lessons/54-html-practice-projects.md)
