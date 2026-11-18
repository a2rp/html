# Example 17 - Navigation and linking between pages

## Question

How can you make a navigation menu that jumps to page sections?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Navigation and linking between pages</title>
</head>
<body>
  <header>
    <h1>Garden guide</h1>
    <nav aria-label="Main navigation">
      <ul>
        <li><a href="#plants">Plants</a></li>
        <li><a href="#care">Care</a></li>
      </ul>
    </nav>
  </header>
  <main>
    <section id="plants">
      <h2>Plants</h2>
      <p>Choose plants suited to the available space.</p>
    </section>
    <section id="care">
      <h2>Care</h2>
      <p>Check light, water, and soil regularly.</p>
    </section>
  </main>
</body>
</html>
~~~

## Expected output

A heading and two navigation links appear. Selecting Plants or Care moves to the matching section.

## Explanation

The nav element identifies a navigation region. Each link uses a fragment that matches the id of its destination section.

## Related lesson

[Read the lesson](../lessons/17-navigation-and-page-links.md)
