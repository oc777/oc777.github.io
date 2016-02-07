---
layout: post
title:  "Robots, Humans, etc"
date:   2015-11-19 00:06:09
description: People, search engines, comments, graphs...
---

Humans
======

Files like _humans.txt_ are created to feed curious people with information. There one hungry human can find the information
about who stands behind a web project - the very people who made it possible and available for others to use.
It is a great place to list everybody involved in the process with their contact information and even to say _thanks_
to those who have helped indirectly.

&nbsp;

It is simple to set up - just add a _humans.txt_ file in the root of your website with the list of the people working on the project
and include a link to it into the `head` section of your page - it's done! There are [some guidelines](http://humanstxt.org/Standard.html)
on how to structure the file, but they are not final.

&nbsp;


Robots
======

Humans are not the only ones surfing the web. There are plenty of spiders too. I am talking about web crawlers - internet robots
that browse the net constantly, mostly for the purpose of indexing and making the content available to users of search engines.
As an owner of a web site you might want to invite those spiders to index some of the pages, but you might also want to hide some
from the "general public". To do so you have to create a _robots.txt_ file where you give the instructions to crawlers
which pages / files / directories they can index and which they shouldn't touch.

&nbsp;

By adding this file to the root of the website you are making it available to the spiders.

However, be aware that they don't have to abide!

&nbsp;

Comments for blog posts
=======

A very simple solution to add comments to your blog is with [Disqus](http://disqus.com). Create an account there and add a snippet
of code they provide to the layout page of your blog section - it is that easy. And hey! You can follow comments of your favourite
blogs in your Disqus account. Leave a comment and tell me what you think!

&nbsp;


Open Graph
=======

When someone wants to share your web page on social media, they need a set of information to post. For example a link to the page,
a picture that represents it, or a video posted there. To make sure that the right _(from your point of view)_ information is
shared, use [Open Graph](http://ogp.me). It turns your page into "a rich object in a social graph". Just add the desired meta data
into the `head` section of your page and take control of how your project is represent when _shared_.



