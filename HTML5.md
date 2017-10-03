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
    </head>
    <body>
        <h1>Headline</h1>
        <p>A paragraph text</p>
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
form | 
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
width | main tag that contains everything
height | main tag that contains everything
style | main tag that contains everything
src | main tag that contains everything
href | main tag that contains everything
title | main tag that contains everything
alt | main tag that contains everything
type | main tag that contains everything
rel | main tag that contains everything
charset | main tag that contains everything


## Tips and tricks

### Inline CSS

### Name the tags yourself

### Importing scripts
You should always import javascripts at the end of your html document. Just before the ending body-tag is recommended.

# Contribute!
Want to help improve this cheatsheet? Just create a pull request and I will look it over :)
