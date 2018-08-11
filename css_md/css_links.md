# css Links

* a:link - a normal, unvisited link
* a:visited - a link the user has visited
* a:hover - a link when the user mouses over it
* a:active - a link the moment it is clicked
>When setting the style for several link states, there are some order rules
>a:hover MUST come after a:link and a:visited
>a:active MUST come after a:hover

## Text Decoration

The text-decoration property is mostly used to remove underlines from links

```css
a:link, a:visited {
    background-color: #f44336;
    color: white;
    padding: 14px 25px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
}


a:hover, a:active {
    background-color: red;
}
```
