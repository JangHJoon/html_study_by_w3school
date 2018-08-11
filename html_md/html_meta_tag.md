# The HTML <meta> Element

The `<meta>` element is used to specify which character set is used, page description, keywords, author, and other metadata.


## example

```html
<meta http-equiv="Content-Type" content="text/html; charset=euc-kr"> 
```
Define MIME and a charset of your web page

```html
<meta http-equiv="pragma" content="no-cache">
```
Web Browser can not save cache, so always request for everything up to date.

```html
<meta http-equiv="expires" content="Wed, 31 Dec 2003 23:59:59 GMT">
```
Set chache expire time


```html
<meta http-equiv="refresh" content="30">
```
Refresh document every 30 seconds


```html
<meta http-equiv="refresh" content="10; url=this.html">
```
Move this site after 10 seconds

```html
<meta name="description" content="Free Web tutorials">
```
Define a description of your web page for search engines

```html
<meta name="keywords" content="HTML, CSS, XML, JavaScript">
```
Define keywords for search engines
