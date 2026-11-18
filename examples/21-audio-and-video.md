# Example 21 - Audio and video

## Question

How can a page provide native audio and video controls?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Audio and video</title>
</head>
<body>
  <main>
    <h1>Garden sounds</h1>
    <audio controls src="media/birds.mp3">
      Audio playback is not available in this browser.
    </audio>
    <h2>Planting demonstration</h2>
    <video controls width="480" poster="media/planting-poster.jpg">
      <source src="media/planting.mp4" type="video/mp4">
      <track src="media/captions.vtt" kind="captions" srclang="en" label="English">
      Video playback is not available in this browser.
    </video>
  </main>
</body>
</html>
~~~

## Expected output

The browser displays native audio and video controls. Playback and the poster image work when the referenced media files are available. Captions can be selected when the track file is valid.

## Explanation

audio and video can use browser controls without a custom player. source can provide media files and track can provide captions. Add media files at the paths used in src.

## Related lesson

[Read the lesson](../lessons/21-audio-and-video.md)
