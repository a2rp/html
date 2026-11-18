# Example 46 - Template elements

## Question

What happens to markup placed inside a template element?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Template elements</title>
</head>
<body>
  <main>
    <h1>Reusable card template</h1>
    <p>The card markup is stored in the document but is not displayed.</p>
    <template id="plant-card">
      <article>
        <h2>Plant name</h2>
        <p>Plant details go here.</p>
      </article>
    </template>
  </main>
</body>
</html>
~~~

## Expected output

The page shows the heading and paragraph. The article inside template does not appear because template content is inert until inserted or used.

## Explanation

template stores markup for later use. The element itself does not render its contents as part of the page. Copying or inserting template content normally requires JavaScript or a component system.

## Related lesson

[Read the lesson](../lessons/46-template-element.md)
