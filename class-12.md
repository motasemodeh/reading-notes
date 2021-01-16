# HTML Images

## Controlling sizes of Images in CSS

You can control the size of an image using the width and height properties in CSS, just like you can for any other box. Specifying image sizes helps pages to load more smoothly because the HTML and CSS code will often load before the images, and telling the browser how much space to leave for an image allows it to render the rest of the page without waiting for the image to download. You might think that your site is likely to have images of all different sizes, but a lot of sites
use the same sized image across many of their pages. For example, an e-commerce site tends to show product photos at the same size. Or, if your site is designed on a grid, then you might have a selection of image
sizes that are commonly used on all pages, such as:

- Small portrait: 220 x 360
- Small landscape: 330 x 210
- Feature photo: 620 x 400

### HTML code

```
<img src="images/magnolia-large.jpg" class="large" alt="Magnolia" />
<img src="images/magnolia-medium.jpg" class="medium" alt="Magnolia" />
<img src="images/magnolia-small.jpg" class="small" alt="Magnolia" />
```
### CSS Code

```
img.large
{
width: 500px;
height: 500px;
}
img.medium
{
width: 250px;
height: 250px;
}
img.small
{
width: 100px;
height: 100px;
}
```

## Background Images

The `background-image` property allows you to place an image behind any HTML element. This could be the entire page or just part of the page. By default, a background image will repeat to fill the entire box. The path to the image follows the letters url, and it is put inside parentheses and quotes


# Practical Information

## Search Engine Optimization (SEO )

SEO is a huge topic and several books have been written on the subject. The following pages will help you understand the key concepts so you can improve your website's visibility on search engines.


Search engine optimization (or mSEO) is the practice of trying to help your site appear nearer the top of search engine results when people look for the topics that your website covers.

SEO is often split into two areas: on-page techniques and off-page techniques.

### On-Page Techniques
On-page techniques are the methods you can use on your web pages to improve their rating in search engines. The main component of this is looking at keywords that people are likely to enter into a search engine if they wanted to find your site, and then including these in the text and HTML code for your site in order to help the search engines know that your site covers these topics.

### Off-Page Techniques
Getting other sites to link to you is just as important as on-page techniques. Search engines help determine how to rank your site by looking at the number of other sites that link to yours. They are particularly interested in sites whose content is related to yours. For example, if you were running a website that sold fish bait, then a link from a hairdresser is not likely to be considered as relevant as one from an angling community.
