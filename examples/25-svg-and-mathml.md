# Example 25 - Inline SVG and MathML in HTML

## Question

How can vector artwork and a math expression be embedded in an HTML document?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Inline SVG and MathML in HTML</title>
</head>
<body>
  <main>
    <h1>Vector and math content</h1>
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 120 80" width="120" height="80" role="img" aria-label="A blue circle">
      <circle cx="40" cy="40" r="30" fill="blue"></circle>
    </svg>
    <p>A simple equation:
      <math xmlns="http://www.w3.org/1998/Math/MathML">
        <mrow><mi>x</mi><mo>=</mo><mn>2</mn></mrow>
      </math>
    </p>
  </main>
</body>
</html>
~~~

## Expected output

A blue circle and a short mathematical expression appear in the page.

## Explanation

SVG describes scalable vector graphics and MathML describes mathematical notation. They use their own element vocabularies and can be embedded in HTML.

## Related lesson

[Read the lesson](../lessons/25-svg-and-mathml.md)
