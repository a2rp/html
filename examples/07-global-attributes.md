# Example 07 - Global attributes

## Question

How can common attributes identify and describe elements?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Global attributes</title>
</head>
<body>
  <main id="main-content" class="page" title="Main page content">
    <h1>Global attributes</h1>
    <p id="summary" class="note">This paragraph has an id and a class.</p>
    <p hidden>This paragraph is hidden.</p>
  </main>
</body>
</html>
~~~

## Expected output

The heading and first paragraph appear. The paragraph with the hidden attribute does not appear.

## Explanation

Global attributes can be used on many HTML elements. id identifies one element, class groups elements, title can provide advisory information, and hidden indicates content that should not be presented.

## Related lesson

[Read the lesson](../lessons/07-global-attributes.md)
