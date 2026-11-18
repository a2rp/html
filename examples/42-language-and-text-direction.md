# Example 42 - Language, text direction, and international content

## Question

How can a page identify text that uses a different language and direction?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Language, text direction, and international content</title>
</head>
<body>
  <main>
    <h1>Language and direction</h1>
    <p lang="en">Welcome to the garden.</p>
    <p lang="ar" dir="rtl">&#1605;&#1585;&#1581;&#1576;&#1575; &#1576;&#1575;&#1604;&#1593;&#1575;&#1604;&#1605;</p>
  </main>
</body>
</html>
~~~

## Expected output

The page shows an English sentence and a right-to-left Arabic greeting.

## Explanation

The lang attribute identifies the language of text. The dir attribute sets its base direction. Mark language and direction on the smallest element that contains the relevant text.

## Related lesson

[Read the lesson](../lessons/42-language-and-text-direction.md)
