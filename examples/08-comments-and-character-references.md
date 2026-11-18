# Example 08 - Comments, character references, and special characters

## Question

How can you write a source comment and display angle brackets as text?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Comments, character references, and special characters</title>
</head>
<body>
  <!-- This note is visible in the source, not on the page. -->
  <main>
    <h1>Comments and characters</h1>
    <p>Write &lt;h1&gt; to show an element name as text.</p>
    <p>Tom &amp; Mina say hello. &copy; 2026</p>
  </main>
</body>
</html>
~~~

## Expected output

The page shows the text <h1> as characters, an ampersand, and a copyright symbol. The comment is not shown.

## Explanation

A comment helps explain source code and is not displayed as page content. Character references such as &lt; and &amp; represent characters that would otherwise be interpreted as markup.

## Related lesson

[Read the lesson](../lessons/08-comments-and-character-references.md)
