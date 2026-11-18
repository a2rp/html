# Example 06 - Nesting, void elements, and HTML syntax

## Question

How do you nest content and include an element that has no end tag?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Nesting, void elements, and HTML syntax</title>
</head>
<body>
  <main>
    <h1>Nested content</h1>
    <ul>
      <li>First item</li>
      <li>Second item</li>
    </ul>
    <p>First line<br>Second line</p>
  </main>
</body>
</html>
~~~

## Expected output

The page shows a heading, a two-item list, and a paragraph split across two lines.

## Explanation

The list items are nested inside ul, which is inside main. The br element is void, so it has no end tag. The tags express nesting; indentation only makes it easier to read.

## Related lesson

[Read the lesson](../lessons/06-nesting-and-html-syntax.md)
