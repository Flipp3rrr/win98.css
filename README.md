# win98.css
Windows 98 inspired CSS, originally created for my NeoCities site https://flipp3rrr.neocities.org/.
## Installation
### Basic CSS
First put the `win98.css` and `mwin98.css` files in the root directory of your site, then adde the code below to the `<head>` in your `html` files to use the CSS. For an example of this see `example.html`.
```html
<link rel="stylesheet" type="text/css" href="/mwin98.css" media="screen, handheld">
<link rel="stylesheet" type="text/css" href="/win98.css" media="screen  and (min-width: 45em)">
```
### Navbar
To use the navbar you need a little bit more code. First put a `<div class="navbar">` in your `<body>`, this is the navbar itself and it will stretch itself to the same width as the rest of your content. Now you can add a `<a href="url">Page</a>` for every page on your site. For the current page it is recommended to also add a `class="active"` to your `<a>` tags. For an examle check `navbar.html`.
```html
<div class="navbar">
    <a href="url">Home</a>
    <a href="url">Page 1</a>
    <a class="active" href="url">(current) Page 2</a>
    <a href="url">Page 3</a>
</div>
```
### Buttons
In the `/buttons/` directory you'll find 88x31 GIF files, these can be used as retro-styled buttons or for information like supported browsers. To edit the original `.piskel` files you should use https://www.piskelapp.com/. Below is an example on how to use these buttons, if you don't want the GIF to be a link simply remove the `<a>` and `</a>`.
```html
<p><a href="url"><img class="smallbutton" src="/buttons/github.gif" alt="View this on my Github"></a></p>
```
