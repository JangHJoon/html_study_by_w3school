# HTML Responsive Web Design


## Setting The Viewport

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```
Set the viewport of your page, which will give the browser instructions on how to control the page's dimensions and scaling.


## Responsive Text Size

The text size can be set with a "vw" unit, which means the "viewport width".
```html
<h1 style="font-size:10vw">Hello World</h1>
```

## Using the width Property

If the CSS width property is set to 100%, the image will be responsive and scale up and down

```html
<img src="img_girl.jpg" style="width:100%;">
```

## Using the max-width Property

If the max-width property is set to 100%, the image will scale down if it has to, but never scale up to be larger than its original size

```html
<img src="img_girl.jpg" style="max-width:100%;height:auto;">
```

## Responsive Table

A responsive table will display a horizontal scroll bar if the screen is too small to display the full content

Add a container element with `overflow-x:auto` around the table element to make it responsive

```html
<div style="overflow-x:auto;">

<table>
 <!-- table content -->
</table>

</div>
```

https://www.w3schools.com/css/tryit.asp?filename=trycss_table_responsive