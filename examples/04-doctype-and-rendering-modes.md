# Example 04 - Doctype and browser rendering modes

## Question

How do you ask a browser to use modern standards mode?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Doctype and browser rendering modes</title>
</head>
<body>
  <h1>Standards mode</h1>
  <p>This document begins with the modern HTML doctype.</p>
</body>
</html>
~~~

## Expected output

A heading and paragraph appear. The doctype itself does not add visible text.

## Explanation

The doctype declaration appears before the html root element. The short modern declaration selects standards mode. It is a declaration, not an HTML element.

## Related lesson

[Read the lesson](../lessons/04-doctype-and-rendering-modes.md)
