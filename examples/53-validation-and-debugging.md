# Example 53 - Validate and debug HTML

## Question

What small valid document can you check with an HTML validator?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Validate and debug HTML</title>
</head>
<body>
  <main>
    <h1>Check this page</h1>
    <p>Every element is placed in a clear document structure.</p>
    <ul>
      <li>Check the opening and closing tags.</li>
      <li>Check that attributes are quoted.</li>
    </ul>
  </main>
</body>
</html>
~~~

## Expected output

The browser shows a heading, paragraph, and two-item list. A conformance checker should report no markup errors for this example.

## Explanation

A validator can identify syntax and conformance problems. It cannot decide whether the page content is useful or whether every choice is accessible, so review the meaning as well.

## Related lesson

[Read the lesson](../lessons/53-validation-and-debugging.md)
