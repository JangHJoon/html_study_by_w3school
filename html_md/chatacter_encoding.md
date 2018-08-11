# HTML Character Encoding


`ASCII` was the first character encoding standard (also called character set). ASCII defined 128 different alphanumeric characters that could be used on the internet: numbers (0-9), English letters (A-Z), and some special characters like ! $ + - ( ) @ < > .

`ANSI` (Windows-1252) was the original Windows character set, with support for 256 different character codes.

`ISO-8859-1` was the default character set for HTML 4. This character set also supported 256 different character codes.

Because ANSI and ISO-8859-1 were so limited, HTML 4 also supported UTF-8.

`UTF-8` (Unicode) covers almost all of the characters and symbols in the world.

The default character encoding for HTML5 is UTF-8.

## The HTML charset Attribute

To display an HTML page correctly, a web browser must know the character set used in the page.

This is specified in the `<meta>` tag:

For HTML4:
```html
<meta http-equiv="Content-Type" content="text/html;charset=ISO-8859-1">
```

For HTML5:
```html
<meta charset="UTF-8">
```

If a browser detects ISO-8859-1 in a web page, it defaults to ANSI, because ANSI is identical to ISO-8859-1 except that ANSI has 32 extra characters.
