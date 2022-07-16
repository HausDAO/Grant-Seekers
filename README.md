---
layout: home
title: DAOhaus Grant Seekers
permalink: /
---
# DAOhaus Grant Seekers
## How to contribute to this repo:

This repo is to track, research and prepare grants to support DAOhaus as a public good.

It is made in the style of a gitbook that uses jekyll, therefore the "book" can be updated with markdown files.
Pages are located in _pages directory
The following must be added to each page created in order for jekyll to recognize the document and render it as a webpage:
```  
  ---
  title: Grant Application
  author: boilerrat
  date: 2022-05-24
  category: Application
  layout: post
+ cover: /assets/jekyll-gitbook/dinosaur.gif
  tag: Grants
  ---
```
If you do not have a cover image, you may delete the "cover" line.

Meeting notes or other "blog" style enteries will follow the same format for metadata as above, however these type of posts can be placed in the _posts directory
