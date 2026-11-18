# Example 13 - Code, abbreviations, dates, and machine-readable text

## Question

How can a page distinguish code, an abbreviation, a date, and a data value?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Code, abbreviations, dates, and machine-readable text</title>
</head>
<body>
  <main>
    <h1>Useful text details</h1>
    <p>Use <code>document.title</code> to read a page title.</p>
    <p><abbr title="HyperText Markup Language">HTML</abbr> structures web pages.</p>
    <p>Updated <time datetime="2026-11-18">18 November 2026</time>.</p>
    <p>Item: <data value="SKU-104">Garden gloves</data>.</p>
  </main>
</body>
</html>
~~~

## Expected output

Readers see a code expression, an abbreviation, a date, and an item name. The title and datetime and data values provide extra machine-readable information.

## Explanation

Specialized text elements describe the kind of text they contain. The datetime and value attributes provide machine-readable values while the element content remains readable.

## Related lesson

[Read the lesson](../lessons/13-specialized-text-elements.md)
