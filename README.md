Assignment: CSS Hell
====================

You will skin 3 project gutenberg stories with custom CSS.

You will skin 2 versions of a possible professional homepage for your
self with 2 versions of CSS.

Read requirements.org

Read this comic http://theoatmeal.com/comics/design_hell

git clone https://github.com/abramhindle/CMPUT404-assignment-css-hell.git

License/Copyright
=================

Textual content is copyright Abram Hindle (C) 2013 under the CC-BY-SA
4.0 unported license. Attribution should be a hyperlink to the
repository and (C) 2013 Abram Hindle visibile in the text.

Contributions from:
  * JingZeng Xie

Code is licensed under the Apache 2.0 license.

Part 1 - Changes of HTML
====================
  * Copy the <code>\<style\></code> from 2.html to theme.css
  * Delete <code>\<style\></code> from all html, and add <code>\<link rel="stylesheet" href="theme.css"\></code> to all html
  * Add <code>\<link rel="coverpage" href="./image/cover.jpg"\></code> to 1.html
  * Delete below <code>\<link\></code> component from all html
 ```html
 <link rel="schema.dc"> 
 <link rel="schema.dcterms"> 
 <link rel="dcterms.isFormatOf">
 ``` 
  * Delete below <code>\<meta\></code> component from all html 
 ```html
 <meta name="dcterms.source"> 
 <meta property="og:url"> 
 <meta property="og:image"> 
 <meta name="generator">
 ```
  * Delete web URL <code>\<a href=\"https:\/\/www.gutenberg.org\/\"\></code> from all html
  * Modify all the href from <code>\<a\></code>, delete the web URL and remain the id of component. E.g. <code><a href="web URL#id"\></code> to <code>\<a href="#id"\></code>
  * Modify all the src from <code>\<img\></code>, change the name of origin finder to image floder
  * Add <code>background: #f3ce8b; font-family: Serif;</code> into body of theme.css
  * Modify <code>class="contents"</code> to all the table of contents from all html, then add the below <code>\<table class="contents"\></code> component to theme.css
 ```css
 table.contents {
	margin-left: auto;
	margin-right: auto;
	font-weight: bold;
}
 ```
  * Add below <code>\<img\></code> component to theme.css
 ```css
 img {
	border: 5px solid #000000;
	width: 60%;
	margin-left: auto;
	margin-right: auto;
	display: block;
}
 ```
  * Add <code>font-weight: bold;</code> to <code>\<h2\></code> component in theme.css
  * Add <code>font-family: "Times New Roman";</code> to <code>\<p\></code> component in theme.css
  
Reference list
====================
  * How to write README.md - https://www.appinn.com/markdown/
  * CSS change the font type - https://www.w3schools.com/css/css_font.asp
  * CSS change the img position - https://segmentfault.com/a/1190000018279674
