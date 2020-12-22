# Structure web pages with HTML

## HTML Structure

### How Pages Use Structure

You can see the HTML code for this page below. Don't worry about what the code means yet.
We start to look at it in more detail on the next page.
```<html>
<body>
<h1>This is the Main Heading</h1>
<p>This text might be an introduction to the rest of
the page. And if the page is a long one it might
be split up into several sub-headings.<p>
<h2>This is a Sub-Heading</h2>
<p>Many long articles have sub-headings so to help
you follow the structure of what is being written.
There may even be sub-sub-headings (or lower-level
headings).</p>
<h2>Another Sub-Heading</h2>
<p>Here you can see another sub-heading.</p>
</body>
</html>
```
`<html>, <body>, <h1>,<p>` these are called HTML elements. HTML uses these Elements to Describe the Structure of Pages

The opening `<html>` tag indicates that anything between it and a closing `</html>` tag is HTML code.
The `<body>` tag indicates that anything between it and the closing
`</body>` tag should be shown inside the main browser window.
Words between `<h1>` and `</h1>` are a main heading.

Extra Markup

Since the web was first created, there have been several different versions of HTML.

Each new version was designed to be an improvement on the last (with new elements and attributes added and older code removed).



DOCTYPEs
`<!DOCTYPE html>`
Because there have been several versions of HTML, each web page should begin with a
DOCTYPE declaration to tell a browser which version of HTML the page is using (although browsers usually display the page even if it is not included). We will therefore be including one in each example for the rest of the book.

Comments in HTML
`<!-- -->`
If you want to add a comment to your code that will not be visible in the user's browser, you
can add the text between these characters:
`<!-- comment goes here -->`
It is a good idea to add comments to your code because, no matter how familiar you are with the page at the time of writing it, when you come
back to it later (or if someone else needs to look at the code), comments will make it much
easier to understand.
Inline Elements
Some elements will always appear to continue on the same line as their neighbouring elements. These are known as inline elements.
Examples of inline elements are
`<a>`, `<b>`, `<em>`, and `<img>`.

Grouping Text & Elements In a Block
`<div>`
The `<div>` element allows you to group a set of elements together in one block-level box.
`<div>` element to contain all of the elements for the header of your site (the logo and the
navigation), or you might create a `<div>` element to contain comments from visitors.

```<div id="header">
<img src="images/logo.gif" alt="Anish Kapoor" />
<ul>
<li><a href="index.html">Home</a></li>
<li><a href="biography.html">Biography</a></li>
<li><a href="works.html">Works</a></li>
<li><a href="contact.html">Contact</a></li>
</ul>
</div><!-- end of header -->
```







## HTML5 Layout

### Traditional HTML Layouts
For a long time, web page authors used <div> elements to group together related elements on the page (such as the elements that form a header, an article, footer or sidebar). Authors used class or id attributes to indicate the role of the <div> element in the structure of the page.

### New Html 5 Layout Elements
HTML5 introduces a new set of elements that allow you to divide up the
parts of a page. The names of these elements indicate the kind of content
you will find in them. They are still subject to change, but that has not
stopped many web page authors using them already.

#### Headers & Footers
`<header>` `<footer>`

The `<header>`and `<footer>` elements can be used for:
● The main header or footer that appears at the top or bottom of every page on the site.
● A header or footer for an individual `<article>` or `<section>` within the page.


#### Figures
`<figure>` `<figcaption>`

You already met the `<figure>` element in Chapter 5 when we looked at images. It can be used to contain any content that is referenced from the main flow of an article (not just images).
