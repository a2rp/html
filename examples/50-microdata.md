# Example 50 - Microdata and structured information

## Question

How can HTML mark visible information as a person and job title?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Microdata and structured information</title>
</head>
<body>
  <main>
    <h1>About the gardener</h1>
    <div itemscope itemtype="https://schema.org/Person">
      <p>Name: <span itemprop="name">Maya Rao</span></p>
      <p>Role: <span itemprop="jobTitle">Community gardener</span></p>
    </div>
  </main>
</body>
</html>
~~~

## Expected output

The page displays a name and role as ordinary text. Microdata attributes add structured meaning in the document source.

## Explanation

itemscope starts a structured item, itemtype identifies its kind, and itemprop labels its properties. The visible content remains readable even when the structured data is not used.

## Related lesson

[Read the lesson](../lessons/50-microdata.md)
