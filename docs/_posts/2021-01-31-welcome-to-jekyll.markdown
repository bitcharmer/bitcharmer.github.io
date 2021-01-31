---
layout: posts
title:  "Taming execution jitter"
date:   2021-01-31 09:07:13 +0000
categories: linux kernel
---

## What is execution jitter (a.k.a. platform jitter, a.k.a. platform noise)

As a computer user you experienced this all too many times. You're using an application such as a browser or a word processor or whatever and suddenly the program just hangs or stutters for a while. Sometimes it's incidental, sometimes it's regular to the point where it ruins your experience or impedes productivity.
In order for any computer program to run it needs to be executed by a CPU(s) in your system. A CPU can only do a single thing at a time so things get complicated quite quickly. 

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
