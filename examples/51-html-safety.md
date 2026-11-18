# Example 51 - Safe links and embedded content

## Question

How can a new-tab link and an embedded document be given safer boundaries?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Safe links and embedded content</title>
</head>
<body>
  <main>
    <h1>External resources</h1>
    <p><a href="https://example.com/" target="_blank" rel="noopener noreferrer">Visit the external site</a></p>
    <iframe
      title="Restricted sample content"
      sandbox=""
      srcdoc="<p>Static embedded content.</p>">
    </iframe>
  </main>
</body>
</html>
~~~

## Expected output

The page shows a link and a small embedded frame. The link opens a new tab when selected, and the iframe sandbox restricts the embedded document.

## Explanation

Use a real destination for links and limit embedded content to the permissions it needs. sandbox applies restrictions to iframe content. Review external content and destinations before including them.

## Related lesson

[Read the lesson](../lessons/51-html-safety.md)
