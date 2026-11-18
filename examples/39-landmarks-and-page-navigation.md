# Example 39 - Landmarks, headings, and accessible page navigation

## Question

How can a skip link help keyboard users reach the main content?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Landmarks, headings, and accessible page navigation</title>
</head>
<body>
  <a href="#main-content">Skip to main content</a>
  <header>
    <h1>Community garden</h1>
    <nav aria-label="Main navigation">
      <a href="#plots">Garden plots</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>
  <main id="main-content">
    <section id="plots">
      <h2>Garden plots</h2>
      <p>Each plot has room for several plants.</p>
    </section>
    <section id="contact">
      <h2>Contact</h2>
      <p>Ask the garden coordinator for details.</p>
    </section>
  </main>
</body>
</html>
~~~

## Expected output

A skip link, page heading, navigation links, and two sections appear. Following a link moves focus or the page location to its target.

## Explanation

Native landmarks and headings provide useful structure. A skip link gives keyboard users a way to bypass repeated navigation and go directly to the main content.

## Related lesson

[Read the lesson](../lessons/39-landmarks-and-page-navigation.md)
