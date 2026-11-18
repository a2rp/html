# Example 28 - Forms: the form element and submission flow

## Question

How can a form collect a name and email address?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Forms: the form element and submission flow</title>
</head>
<body>
  <main>
    <h1>Contact us</h1>
    <form action="/contact" method="post">
      <p><label for="name">Name</label>
        <input id="name" name="name" autocomplete="name" required></p>
      <p><label for="email">Email</label>
        <input id="email" name="email" type="email" autocomplete="email" required></p>
      <button type="submit">Send message</button>
    </form>
  </main>
</body>
</html>
~~~

## Expected output

The page displays two labeled fields and a submit button. Submitting requires a server at /contact to receive and process the form data.

## Explanation

form groups controls into a submission. Each control needs a name for its submitted value, and each visible label identifies its control. The action path is an example endpoint, not a working service.

## Related lesson

[Read the lesson](../lessons/28-forms-overview.md)
