# Example 55 - HTML quick reference and glossary

## Question

How can a description list present a small HTML glossary?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>HTML quick reference and glossary</title>
</head>
<body>
  <main>
    <h1>HTML glossary</h1>
    <dl>
      <dt>Element</dt>
      <dd>A unit of HTML structure and meaning.</dd>
      <dt>Attribute</dt>
      <dd>Additional information written in an element's start tag.</dd>
      <dt>Void element</dt>
      <dd>An element that cannot contain content and has no end tag.</dd>
    </dl>
  </main>
</body>
</html>
~~~

## Expected output

The page shows three terms, each followed by its description.

## Explanation

dl groups terms with their descriptions. dt marks each term and dd gives the corresponding explanation. The list structure makes each pair clear to readers and browsers.

## Related lesson

[Read the lesson](../lessons/55-html-reference-and-glossary.md)
