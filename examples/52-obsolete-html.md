# Example 52 - Deprecated elements and obsolete HTML

## Question

Which modern elements can express meaning that old presentational tags could not?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Deprecated elements and obsolete HTML</title>
</head>
<body>
  <main>
    <h1>Modern semantic markup</h1>
    <p><strong>Important:</strong> Check the label before using a product.</p>
    <p><del>Old price: $12</del> <ins>New price: $10</ins></p>
    <ul>
      <li>Use headings for headings.</li>
      <li>Use CSS for visual styling.</li>
    </ul>
  </main>
</body>
</html>
~~~

## Expected output

The page shows important text, marked old and new text, and a list. It does not rely on obsolete font or strike elements.

## Explanation

Modern HTML uses elements for meaning and CSS for presentation. strong marks importance, del and ins mark edits, and headings or lists should use their semantic elements.

## Related lesson

[Read the lesson](../lessons/52-obsolete-html.md)
