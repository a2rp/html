# Example 22 - The iframe element and embedded pages

## Question

How can you embed a small HTML document inside another page?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>The iframe element and embedded pages</title>
</head>
<body>
  <main>
    <h1>Embedded message</h1>
    <iframe
      title="A message from another document"
      srcdoc="<p>Hello from the embedded document.</p>">
    </iframe>
  </main>
</body>
</html>
~~~

## Expected output

The page shows a heading and a small framed area containing the embedded message.

## Explanation

iframe creates a nested browsing context. The title describes the frame to assistive technology. The srcdoc attribute supplies a small HTML document directly.

## Related lesson

[Read the lesson](../lessons/22-iframes-and-embedded-pages.md)
