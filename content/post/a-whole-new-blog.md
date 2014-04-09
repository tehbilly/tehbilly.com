---
draft: false
title: "Blogging again"
description: "Reviving tehbilly.com as a hugo-powered blog"
date: "2014-04-08"
categories:
  - "development"
tags:
  - "golang"
  - "hugo"
---

Making another attempt at blogging. Nothing fancy this time, just using [hugo](http://hugo.spf13.com/): a wonderful
static site generator written in [go](http://golang.org/). I have quite a bit I plan to share in the near future,
including my adventures as a father and my advancements as a developer.

Hugo
----

I discovered [hugo](http://hugo.spf13.com/) some time ago as I was looking at what popular/interesting projects written
in [go](http://golang.org/). For those interested in a static site generator in general, or a very straightforward
blogging method, I highly recommend it. Essentially I get to write content in markdown with some templates and **bam**,
efficient static html content is generated. I then use [github pages](https://pages.github.com/) to serve the generated
static content and all's well. I'll probably blog more in depth about it in the near future, along with a much needed
template project to help others trying to get started quickly.

Being a Father
--------------

It's pretty much the coolest thing ever sometimes.

Front Matter For Fun
--------------------

This is the meta data for this post. At the top of the markdown file. Pretty damn easy. Considering adding highlight.js
as a hugo shortcode. I'm too tired.

````yaml
---
draft: false
title: "Blogging again"
description: "Reviving tehbilly.com as a hugo-powered blog"
date: "2014-04-08"
categories:
  - "development"
tags:
  - "golang"
  - "hugo"
---
````