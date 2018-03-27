# Welcome to the HTML5 Cheat Sheet
A great tool for new users when building websites. Checkout the [wikipedia](https://en.wikipedia.org/wiki/HTML) if you are unsure about that HTML is.

## HTML-tag markup
```html
<tagname attribute="value"></tagname>
```

## Simple website
```html
<!DOCTYPE html>
<html>
    <head>
        <title>Website Title</title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
    </head>
    <body>
        <h1>Headline</h1>
        <p>A paragraph text</p>
    </body>
</html>
```

## Website with external script- and style-files
```html
<!DOCTYPE html>
<html>
    <head>
        <title>Website Title</title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" type="text/css" href="mystyles.css">
    </head>
    <body>
        <h1>Headline</h1>
        <p>A paragraph text</p>

        <script src="myscripts.js"></script>
    </body>
</html>
```

## Important notes
* ```<!DOCTYPE html>``` should be user to tell the browser that this is a html5 document
* Most HTML-tags need an ending tag but not all, like the link, meta and br tag.
* The biggest differans between differant tagnames is the default CSS styling they have, wich always can be overwriten. BUT some tags have special functions that none of the other tags have. The form- and a-tag for example.


## Common Tagnames

Tagname | Description
---------- | ------------------
html | The main tag that contains everything
head | Contains everything that is invisible on the websites frame, like webpage title and styling imports
body | Contains all the visible stuff on your website
meta | Is used to add some metadata to the website, like encoding and SEO stuff
link | Is used to import styling files using the src-attribute
script | Is used to import javascript files using the src-attribute
form | Used to wrapp a lot of input tags, in order to submit the data to a server after clicking submit
div | A container-tag that has default css display:block, otherwise nothing speciall
span | A container-tag that has default css display:inline, otherwise nothing speciall
main | Same as div, but is used to contain the main section of the website
nav | Same as div, but is used to contain the navigation section
section | Same as div, but is used to contain a section of the website
article | Same as div, but is used to contain an article, like a blogpost or likewise
aside | Same as div, but is used to contain the sidebar content
header | Same as div, but is used to contain the main header section of the website
footer | Same as div, but is used to contain the main footer of the website
video | Video-tag, Add the src-attribute and you can play a video
audio | Audio-tag, add the src-attribute and you can listen to an audiofile
img | Image-tag, add the src-attribute and you can display an image
h1-6 | Headline text from font size 2em(1) to .67em(6)
p | A paragraph tag, uselly used with large amount of texts. Good to know that it has large default margins on top and bottom
a | A link-tag, can with the 'href'-attribute create a clickable link
br | Linebreak, will break the line with the current line-height


## Common Attributes

Attribute Name | Description
---------- | -------------------------------
width | The width of the element
height | The height of the element
style | Used to write inline css that is only used for this element
src | Used on images, scripts-tags and style-tags to link to the source data for the tag, for example a path to an image or css file
href | Makes an a-tag och a button-tag link to a specific url
title | The title of an element, creates a tooltip over images on hover, also great for "read website out loud" programs
alt | Old way of setting the title of an image, may still have some other functions aswell
type | Specifies the type of a linked resource, for example a "text/css"-type
rel | Tells the browser how it should see the resource, for example a "stylesheet"
charset | Used on a meta-tag inside the head section, lets the browser know that this is a for example "UTF-8" webpage


## Tips and tricks
Use CSS Grid to line elements up!
Not written yet.

### Inline CSS
Not written yet.

### Name the tags yourself
Not written yet.

### Importing external resources
You should always import javascripts at the end of your html document, just before the body's end-tag. CSS files should be imported in the head section as usual.

# Great resources
[Google PageSpeed Insight](https://developers.google.com/speed/pagespeed/insights/) - To meschure a websites loading times and getting tips on how to improve it
[Official Mozzila HTML Documentation](https://developer.mozilla.org/en-US/docs/Web/HTML/Element) - Info about all of the normal html tags
[HTML5 Developers Documentation](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5) - Info about all the new functions that HTML5 comes with
[W3's HTML Syntax Checker](https://validator.w3.org/) - Great for finding unneeded and rendundant elements on a big website

# Contribute!
Want to help improve this cheatsheet? Just create a pull request and I will look it over :)
