# css Selector

## The element Selector

The element selector selects elements based on the element name.

```css
p {
    text-align: center;
    color: red;
}
```

## The id Selector

The id selector uses the id attribute of an HTML element to select a specific element.

The id of an element should be unique within a page, so the id selector is used to select one unique element!

To select an element with a specific id, write a hash (#) character, followed by the id of the element.

```css
#para1 {
    text-align: center;
    color: red;
}
```

## The class Selector

The class selector selects elements with a specific class attribute.

To select elements with a specific class, write a period (.) character, followed by the name of the class.

```css
.center {
    text-align: center;
    color: red;
}
```
 
* HTML elements can also refer to more than one class.
```html
<p class="center large">
```
The `<p>` element will be styled according to `class="center"` and to `class="large"`
 
 ### element Selector + class Selecter

```css
p.center {
    text-align: center;
    color: red;
}
```

### element Selector + id Selector
```css
p#center {
    text-align: center;
    color: red;
}
```
