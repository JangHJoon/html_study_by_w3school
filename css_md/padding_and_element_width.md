# Padding and Element Width

The CSS width property specifies the width of the element's content area. The content area is the portion inside the padding, border, and margin of an element (the box model).

So, if an element has a specified width, the padding added to that element will be added to the total width of the element. This is often an undesirable result.


In the following example, the `<div>` element is given a width of 300px. However, the actual rendered width of the `<div>` element will be 350px (300px + 25px of left padding + 25px of right padding):

```css
div {
    width: 300px;
    padding: 25px;
}
```

To keep the width at 300px, no matter the amount of padding, you can use the box-sizing property. This causes the element to maintain its width; if you increase the padding, the available content space will decrease. 

```css
div {
    width: 300px;
    padding: 25px;
    box-sizing: border-box;
}
```

Note: The height and width properties do not include padding, borders, or margins; they set the height/width of the area inside the padding, border, and margin of the element!