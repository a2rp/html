# Example 23 - Embedding external content safely

## Question

How can an embedded document be sandboxed?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Embedding external content safely</title>
</head>
<body>
  <main>
    <h1>Safe embedded content</h1>
    <iframe
      title="A sandboxed greeting"
      sandbox=""
      srcdoc="<p>This embedded document has no script permission.</p>">
    </iframe>
  </main>
</body>
</html>
~~~

## Expected output

The browser displays a frame containing the greeting. The empty sandbox attribute applies restrictions to the embedded document.

## Explanation

An iframe can load content from another page. The sandbox attribute restricts capabilities by default. Grant extra permissions only when the embedded content needs them.

## Related lesson

[Read the lesson](../lessons/23-safe-embedded-content.md)
