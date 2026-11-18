# Example 24 - Responsive images: picture, srcset, and sizes

## Question

How can a page offer different image sources for different viewport sizes?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Responsive images: picture, srcset, and sizes</title>
</head>
<body>
  <main>
    <h1>Responsive image</h1>
    <picture>
      <source media="(min-width: 800px)" srcset="images/garden-wide.jpg">
      <img src="images/garden-small.jpg" alt="A small vegetable garden" width="600">
    </picture>
  </main>
</body>
</html>
~~~

## Expected output

The browser chooses the wide source when the media condition matches and the file exists. Otherwise it uses the img fallback source.

## Explanation

picture and source let the browser choose among image files. img remains the fallback and provides the alternative text. Put the image files at the paths shown or change the paths.

## Related lesson

[Read the lesson](../lessons/24-responsive-images.md)
