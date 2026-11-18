# Example 41 - ARIA in HTML: when and how to use it

## Question

How can ARIA clarify the current page link in a navigation region?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>ARIA in HTML: when and how to use it</title>
</head>
<body>
  <nav aria-label="Main navigation">
    <a href="index.html" aria-current="page">Home</a>
    <a href="about.html">About</a>
    <a href="contact.html">Contact</a>
  </nav>
  <main>
    <h1>Home</h1>
    <p>Welcome to the garden guide.</p>
  </main>
</body>
</html>
~~~

## Expected output

The page shows a navigation region with three links. Assistive technology can identify Home as the current page.

## Explanation

ARIA can add information that native HTML does not already provide. Prefer native elements and use ARIA only when it supplies a needed accessible name, state, or relationship.

## Related lesson

[Read the lesson](../lessons/41-aria-in-html.md)
