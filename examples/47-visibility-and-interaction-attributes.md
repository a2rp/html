# Example 47 - Hidden, inert, tabindex, and editable content

## Question

How do hidden, inert, tabindex, and contenteditable affect page elements?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Hidden, inert, tabindex, and editable content</title>
</head>
<body>
  <main>
    <h1>Interaction attributes</h1>
    <p hidden>This message is not displayed.</p>
    <section inert>
      <h2>Unavailable section</h2>
      <button type="button">Unavailable action</button>
    </section>
    <p tabindex="0">This paragraph can receive keyboard focus.</p>
    <p contenteditable="true">Select this text and edit it.</p>
  </main>
</body>
</html>
~~~

## Expected output

The hidden paragraph is not shown. The inert section is unavailable for interaction. The focusable paragraph can receive keyboard focus, and the final paragraph can be edited.

## Explanation

These attributes have different purposes. hidden removes content from presentation, inert disables interaction in a subtree, tabindex affects focusability, and contenteditable allows editing.

## Related lesson

[Read the lesson](../lessons/47-visibility-and-interaction-attributes.md)
