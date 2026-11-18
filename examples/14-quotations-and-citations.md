# Example 14 - Quotations and citations

## Question

How can you mark a longer quotation and identify its source?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Quotations and citations</title>
</head>
<body>
  <main>
    <h1>A quotation</h1>
    <blockquote cite="https://example.com/gardening">
      <p>Good soil gives a garden a strong start.</p>
    </blockquote>
    <p>The words are quoted from <cite>Gardening Basics</cite>.</p>
  </main>
</body>
</html>
~~~

## Expected output

The quotation appears as a separate block, followed by a sentence naming the work.

## Explanation

blockquote marks a longer quotation. cite marks the title of a creative work. The cite attribute can provide the source URL, but it is not usually shown as visible text.

## Related lesson

[Read the lesson](../lessons/14-quotations-and-citations.md)
