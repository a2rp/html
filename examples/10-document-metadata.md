# Example 10 - Metadata: charset, viewport, and description

## Question

Which metadata can describe encoding, mobile viewport, and page summary?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="description" content="A short guide to growing herbs at home.">
  <title>Growing herbs</title>
</head>
<body>
  <main>
    <h1>Growing herbs</h1>
    <p>Start with a bright place and a suitable pot.</p>
  </main>
</body>
</html>
~~~

## Expected output

The visible page shows a heading and paragraph. The encoding, viewport, and description settings are not displayed as page text.

## Explanation

Metadata belongs in head. The charset declares the document encoding, the viewport setting helps mobile browsers choose a layout width, and the description provides a short summary for software that uses it.

## Related lesson

[Read the lesson](../lessons/10-document-metadata.md)
