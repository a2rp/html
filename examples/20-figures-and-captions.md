# Example 20 - Figures and captions

## Question

How can an image and its caption be grouped together?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Figures and captions</title>
</head>
<body>
  <main>
    <h1>Garden journal</h1>
    <figure>
      <img src="images/seedlings.jpg" alt="Young seedlings in small pots">
      <figcaption>Seedlings started indoors in early spring.</figcaption>
    </figure>
  </main>
</body>
</html>
~~~

## Expected output

When the image file exists, it appears with a caption beneath or beside it according to browser styling. The caption remains associated with the image.

## Explanation

figure groups self-contained content. figcaption provides its caption. The image still needs alternative text for people who cannot see it.

## Related lesson

[Read the lesson](../lessons/20-figures-and-captions.md)
