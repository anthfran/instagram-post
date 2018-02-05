[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/anthfran/instagram-post)

# \<instagram-post\>

Display an Instagram image post in your Polymer website

## Demo

https://www.webcomponents.org/element/anthfran/instagram-post/demo/demo/index.html

## Installation

`bower install --save anthfran/instagram-post`

## Usage

### Include this custom element
`<link rel="import" href="../bower_components/instagram-post/instagram-post.html">`

### Find your post id

For example the post id for (https://www.instagram.com/p/BeY1pSzBl2f/) is BeY1pSzBl2f

### Add to your app
<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="instagram-post.html">
    <next-code-block></next-code-block>  
    </template>
</custom-element-demo>
```
-->
```html
<instagram-post postid="BeY1pSzBl2f"></instagram-post>
```
## History
Feb  5, 2018 - v1.2.0 - Implemented multiple image posts

Jan 29, 2018 - v1.1.0 - Implemented video support

Jan 27, 2018 - v1.0.0 - First release. Only support for single image
