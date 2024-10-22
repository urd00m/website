---
layout: post
title: Upgrading the Blog
categories: General
tags: General Website
---

I finally got around to doing some website updates as a break from research.
I've been wanting to do some website updates for some time. 
I've also wanted to create a better way to track just general notekeeping and readings I've done. 
So naturally, the website update I wanted to do was upgrading the blog to also contain notes of any kind (like notes on papers) :D

One might think that this is a rather easy change, just create two different blogs right? 
Each would contain posts from different categories like security paper reads and general blogs. 
This unfortunately **does not work** and after spending a couple hours trying to hack Jekyll to do this I gave up. 
The problem is that Jekyll assumes one blog and just naturally accumlates everything into one blog. 
Paginator assumes the same thing (though there is V2 which apparently supports multiple categories, github pages does not support V2). 

The next step was to search online for hints since I'm definitely not the first to tackle this problem. 
I stumbled across this website [here](http://anandmanisankar.com/) which actually did something better. 
Instead of creating multiple blogs you can instead **tag posts and then organize everything with tags**. 
So I basically grabbed portions that I wanted and inserted it into the blog. 
I did make a lot of modifications, but I would rather not drone on about those changes. 
Ultimately, the blog now supports tags and the display is collapsable to avoid clutter (I need to figure out how my advisor got the cool buttons on his page). 
It will be nice to be able to upload notes here now to just be more easily accessible to me (the tag search feature is really nice). 

Summary of things I did
* Jekyll doesn't support separating blog posts :\ 
* Trying to hack Jekyll to support multiple blog categories was not fun 
* Stumbled across this [website](http://anandmanisankar.com/) and grab the fun code
* Initially started with the default blog post page and an archive page
* Found that after expanding pagination to 5 there were ghost pages where "Reading" pages weren't displayed (by design)
* Decided I hated the ghost pages and switched directions
* Combined all the blog pages into one to make the sidebar easy to read
* Blog page was now wayyyyy too cluttered
* Solution to clutter --> collapsable categories :D 
* Added the "See All" section to just make it easier to search stuff 
* Starting to write lots and lots of stuff to put online

ʘ‿ʘ

