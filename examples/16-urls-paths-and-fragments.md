# Example 16 - URLs, file paths, and page fragments

## Question

How can links point to another file or a section on the current page?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>URLs, file paths, and page fragments</title>
</head>
<body>
  <nav aria-label="Page contents">
    <a href="about.html">About this site</a>
    <a href="#contact">Contact section</a>
  </nav>
  <main>
    <h1>Garden site</h1>
    <section id="about">
      <h2>About</h2>
      <p>Notes for a small garden.</p>
    </section>
    <section id="contact">
      <h2>Contact</h2>
      <p>Email the garden team.</p>
    </section>
  </main>
</body>
</html>
~~~

## Expected output

The page shows two navigation links and two sections. The contact link moves to the section whose id is contact. The about link opens about.html if that file exists in the same folder.

## Explanation

A relative URL such as about.html is resolved from the current file's location. A fragment such as #contact points to an element with a matching id.

## Related lesson

[Read the lesson](../lessons/16-urls-paths-and-fragments.md)
