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
  * Delete <code>\<style\></code> from all html, and add <code>\<link rel="stylesheet" href="theme.css"\></code> to all html.
  * Add <code>\<link rel="coverpage" href="./image/cover.jpg"\></code> to 1.html
  * Delete <code>\<link rel="schema.dc"\> \<link rel="schema.dcterms"\> \<link rel="dcterms.isFormatOf"\></code> from all html
  * Delete <code>\<meta name="dcterms.source"\> \<meta property="og:url"\> \<meta property="og:image"\> \<meta name="generator"\></code> from all html
  * Delete web URL <code>\<a href=\"https:\/\/www.gutenberg.org\/\"\></code> from all html
  * Delete all the web URL from the href, and remain the id of component. E.g. <code><a href="web URL#chap01"\></code> to <code>\<a href="#chap01"\></code>
  
Reference list
====================
  * How to write README.md - https://www.appinn.com/markdown/
