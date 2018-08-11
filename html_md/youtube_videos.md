# YouTube Videos

The easiest way to play videos in HTML, is to use YouTube.

Struggling with Video Formats?
Earlier in this tutorial, you have seen that you might have to convert your videos to different formats to make them play in all browsers.

Converting videos to different formats can be difficult and time-consuming.

An easier solution is to let YouTube play the videos in your web page.

## Using <iframe> (recommended)
```html
<iframe width="420" height="315"
src="https://www.youtube.com/embed/tgbNymZ7vqY">
</iframe>
```

## Using <object> (deprecated)
```html
<object width="420" height="315"
data="https://www.youtube.com/embed/tgbNymZ7vqY">
```
</object>
## Using <embed> (deprecated)
```html
<embed width="420" height="315"
src="https://www.youtube.com/embed/tgbNymZ7vqY">
```