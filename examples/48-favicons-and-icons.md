# Example 48 - Favicons and document icons

## Question

How can a document point browsers to a favicon file?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Garden journal</title>
  <link rel="icon" href="favicon.svg" type="image/svg+xml">
</head>
<body>
  <main>
    <h1>Garden journal</h1>
    <p>Check the browser tab for the document icon.</p>
  </main>
</body>
</html>
~~~

## Expected output

The page shows a heading and paragraph. The browser can show favicon.svg in the tab when that file exists at the specified path.

## Explanation

A link element with rel=icon identifies a document icon. The example references a separate image file, so add favicon.svg beside the HTML page or update the href.

## Related lesson

[Read the lesson](../lessons/48-favicons-and-icons.md)
