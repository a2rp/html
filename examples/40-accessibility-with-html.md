# Example 40 - Accessibility with native HTML

## Question

How can native HTML give images, links, and controls clear names?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Accessibility with native HTML</title>
</head>
<body>
  <main>
    <h1>Accessible garden guide</h1>
    <img src="images/seedling.jpg" alt="A young seedling with two leaves">
    <p><a href="watering.html">Read the watering guide</a></p>
    <form>
      <label for="email">Email address</label>
      <input id="email" name="email" type="email" required>
      <button type="submit">Subscribe</button>
    </form>
  </main>
</body>
</html>
~~~

## Expected output

A page heading, an image when its file is available, a descriptive link, and a labeled email form appear.

## Explanation

Native HTML provides built-in semantics and interaction. Informative images need useful alternative text, links need descriptive text, and controls need associated labels.

## Related lesson

[Read the lesson](../lessons/40-accessibility-with-html.md)
