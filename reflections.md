>* Trees represent data that makeup websites: A parent branch `<ul>` has many children `<li></li>`.

>* DOCTYPE: Describes the type of HTML. `<!DOCTYPE html>` helps the browser determine what type of HTML document it’s trying to parse and display.

>* Browsers look for this doctype declaration to determine which rendering mode to use to render the site. Generally, newer sites follow standard HTML specifications. The current standard HTML specification is called HTML5.

>* `<head>` Describes meta information about the site, such as the title, and provides links to scripts and stylesheets the site needs to render and behave correctly.

>* `<body>` Describes the actual content of the site that users will see.

>* To open the web development tools on a Mac: Command + Option + i

>* apply `<style>` tag to apply css to a page.

>* apply `<script type="text/javascript">` tag to apply javascript to a page.
>* CSS measurement units can be: _absolute-_ (100px/in/cm/mm) fixed units of measurement. _relative-_ (100%/em/vw -viewport width-/vh -viewport height-) units that are a comparison to another linked property.

## HTML5 Semantic Elements    
>- `<header>` - Defines a header for a document or a section
>- `<nav>` - Defines a container for navigation links
>- `<section>` - Defines a section in a document
>- `<article>` - Defines an independent self-contained article
>- `<aside>` - Defines content aside from the content (like a sidebar)
>- `<footer>` - Defines a footer for a document or a section
>- `<details>` - Defines additional details
>- `<summary>` - Defines a heading for the `<details>` element

---
  1. What CSS property is used to __italicize__ text? font-style
  2. What CSS property is used to __underline__ text? text-decoration
  3. What CSS property is used to __uppercase__ text? text-transform
  4. What CSS property is used to __bold__ text? font-weight

  5. Which HTML elements match the given CSS statement?
```
  .right {
       text-align: right;
  }

<div class="right"></div>
<p class="highlight module right"></p>
```

6. The `font-family` property is used to _change the font_ to Helvetica, Arial, or the default sans-serif font installed on the operating system.

7. The `font-size` property is used to increase the _size of the font_ to be larger

8. The `text-transform` and `text-decoration` properties are used to _capitalize_ and _underline_ the text.

9. Color is used to change the color.
10. Every CSS statement is made up of a selector and a declaration block. The __selector__ tells the browser what HTML element we want to style and the __declaration block__ tells the browser what styles need to be applied to that HTML.

---
>- A stylesheet is a file containing the code that describes how elements on your webpage should be displayed.

>- To link your stylesheet to your html file, you'll need to create a <link> to your stylesheet in your HTML.

```
<link href="path-to-stylesheet/stylesheet.css" rel="stylesheet">
```

>- The href attribute specifies the path to the linked resource and the rel attribute names the relationship between the resource and your document.

```
<head>
  <title>My Webpage</title>
  <!-- ... -->
  <link href="path-to-stylesheet/stylesheet.css" rel="stylesheet">
  <!-- ... -->
</head>
```