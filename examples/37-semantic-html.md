# Example 37 - Semantic HTML and page structure

## Question

How can semantic elements describe the roles of page regions?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Semantic HTML and page structure</title>
</head>
<body>
  <header>
    <h1>Garden journal</h1>
  </header>
  <main>
    <article>
      <h2>Growing basil</h2>
      <p>Basil grows well in a warm, bright place.</p>
    </article>
    <aside>
      <h2>Related note</h2>
      <p>Water the soil when its surface begins to dry.</p>
    </aside>
  </main>
  <footer>
    <p>Garden journal</p>
  </footer>
</body>
</html>
~~~

## Expected output

The page shows a site heading, an article, a related note, and a footer. These elements communicate structure in addition to their default appearance.

## Explanation

Semantic elements describe the purpose of their content. Choose them for meaning. CSS can change appearance without changing the meaning of the HTML.

## Related lesson

[Read the lesson](../lessons/37-semantic-html.md)
