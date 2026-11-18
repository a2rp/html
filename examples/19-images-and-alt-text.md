# Example 19 - Images and alternative text

## Question

How do you add an image with alternative text?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Images and alternative text</title>
</head>
<body>
  <main>
    <h1>Tomato plants</h1>
    <img src="images/tomato-plants.jpg" alt="Tomato plants growing beside a garden fence" width="480">
  </main>
</body>
</html>
~~~

## Expected output

If the image file exists at the given path, the browser shows it. If it is unavailable, the alternative text helps explain the image's purpose.

## Explanation

The img element embeds an image. Give an informative image a concise alt description. Put the image file in the matching images folder or update src to its actual path.

## Related lesson

[Read the lesson](../lessons/19-images-and-alt-text.md)
