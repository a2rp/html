# Example 43 - Details and summary

## Question

How can you make a simple disclosure that opens without a script?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Details and summary</title>
</head>
<body>
  <main>
    <h1>Plant care</h1>
    <details>
      <summary>How often should I water basil?</summary>
      <p>Check the soil and water when its surface begins to dry.</p>
    </details>
  </main>
</body>
</html>
~~~

## Expected output

A disclosure summary appears. Selecting it reveals or hides the answer using the browser's built-in behavior.

## Explanation

details provides a native disclosure widget. summary supplies its visible label. This basic open and close interaction does not need JavaScript.

## Related lesson

[Read the lesson](../lessons/43-details-and-summary.md)
