---
layout: post
title:  "Dynamic Page Content (Part 1)"
date:   2017-05-26 13:32:00 -0800
categories: tutorials
---

One of the things that originally drew me to programming was the ability to automate repetitive tasks. Recently I realized a task I repeat every few days could be drastically simplified if I wrote some code to automate most of the steps I take each time. But first, here's a little backstory. 

# Backstory

A few months ago I decided to save every [GIF](http://howtoreallypronouncegif.com/) I use just in case I decided to use it again in the future. I created a page on my personal site to store and display these GIFs. After a couple of iterations, I came up with the following HTML for this page (Note: the site uses [Bootstrap 3](http://getbootstrap.com)):

```
<div class="container">
    <div class="row">
        <div class="col-lg-3 col-md-4 col-sm-6">
            <a class="title-link" href="/assets/gifs/gif-1.gif" target="_blank">GIF 1 Title</a>
            <hr />
            <!-- Source: {GIF 1 source URL} -->
            <div class="gif-container">
                <img src="/assets/gifs/gif-1.gif" title="GIF 1 Title" />
            </div><!-- gif-container -->
        </div><!-- col -->
        <div class="col-lg-3 col-md-4 col-sm-6">
            <a class="title-link" href="/assets/gifs/gif-2.gif" target="_blank">GIF 2 Title</a>
            <hr />
            <!-- Source: {GIF 2 source URL} -->
            <div class="gif-container">
                <img src="/assets/gifs/gif-2.gif" title="GIF 2 Title" />
            </div><!-- gif-container -->
        </div><!-- col -->
        <div class="col-lg-3 col-md-4 col-sm-6">
            <a class="title-link" href="/assets/gifs/gif-3.gif" target="_blank">GIF 3 Title</a>
            <hr />
            <!-- Source: {GIF 3 source URL} -->
            <div class="gif-container">
                <img src="/assets/gifs/gif-3.gif" title="GIF 3 Title" />
            </div><!-- gif-container -->
        </div><!-- col -->
    </div><!-- row -->
</div><!-- column -->
```

This worked just fine for a while; by the time I got around to creating this page I had a stash of GIFs to create this page with. I wasn't adding new ones very often, so copy/pasting from the existing structure wasn't a big deal. But this got old fast. 

-----

# todo


-----

> [The Final Result](http://pico.bluesaltlabs.com/personal/gifs)   

<p style="text-align: right;"> - Luke</p>


<!--
todo: add syntax highlighting to this page with [highlight.js](https://highlightjs.org/)

<https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/>
`bundle exec jekyll serve`

<https://jekyllrb.com/docs/usage/>
`jekyll build --watch`
-->