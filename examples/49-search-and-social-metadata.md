# Example 49 - Search and social sharing metadata

## Question

How can head metadata describe a page to search and sharing tools?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="description" content="Practical notes for growing herbs in containers.">
  <meta property="og:title" content="Container herb garden">
  <meta property="og:description" content="A short guide to growing herbs in pots.">
  <title>Container herb garden</title>
</head>
<body>
  <main>
    <h1>Container herb garden</h1>
    <p>Choose a suitable pot, soil, and sunny place.</p>
  </main>
</body>
</html>
~~~

## Expected output

The visible page shows a heading and paragraph. Description and Open Graph metadata are stored in the document head and are not shown as page text.

## Explanation

Metadata can summarize a page for software that reads it. Search or social services may use these values, but they may choose different text when presenting a result.

## Related lesson

[Read the lesson](../lessons/49-search-and-social-metadata.md)
