---
author: Affan Abiyyu
pubDatetime: 2023-03-27T05:59:00Z
title: Trying to make a simple website using AstroJS V2
postSlug: devlog-1
featured: false
draft: false
tags:
  - dev-log
  - log
ogImage: ""
description: My first web developer notes on making this website.
---

## Why make a website

From a long time ago (during college, high school, even elementary school) there was an interest in making a website. When I was in elementary school, I made a website using a platform called xtgem, a cellphone website like waptrick, filled with pictures / java games with my friends. And in college I also learned how to make a web. Finally interested in Front-End. Now that I'm not in college, and confused about what to make, maybe it's better to make a personal web. I don't know what the result will be (?) Filled in while learning.

The plan for now, the purpose of this website:

- learn basic front-end again (html, css, js, typescript)
- learn astro js, the framework for this website
- learn svelte, because in astro you can use svelte
- will be filled with my writing / work, which I don't know if anyone will read or not
- practice writing articles (?) so that I can be articulate to tell my point, and can be useful for people
- documentation of my processes

In essence, everything that is unspoken but can be written, may be written here.

## Why Astro JS

The first time I tried Front-End was during my internship, at a Surabaya startup called Aegis. I was taught to use the Svelte framework, and really liked it because it was powerful.

Svelte's shortcoming was that it was client-rendered, where all website elements were rendered in the client's browser. As a result, the SEO of the website is not good (?) So it is only suitable for web-apps, not for websites that contain information.

> For example, if there is a blog about something, Google can pick up on that something. Because Google understands, so our website is likely to appear in Google search. If the website is rendered on the client, then it can't be read by Google, because the html file has not been rendered. It is rendered when the javascript is executed, in the browser. Meanwhile, Google's robot doesn't render websites one by one, it uses other technology, if you call it crawling,

So at that time I could only do html, css, js, and a little svelte.
But I wanted to make something that could be like a blog.
Finally found Astro.

Astro JS is basically a Static Site Generator.
So it's not client-rendered, and it also doesn't use a server (not server-rendered).

And the good thing is, the website can be hosted for free on github.

And also when I first knew astro, it was still version 1, and now it's version 2, it's really fast.
I think the growth of the community is fast, and the developers are passionate, so I just tried to explore this framework.

Another advantage of astro is that it can render elements with .svelte language, even react or vue. So it's flexible. (_only I don't really understand this one, I'll post it here as I go along if I understand it better_)

Plus, in version 2 of Astro, there is such a thing as **content collections**. So you can fill in other types of content besides blogs, like items, or maybe galleries. I'll find out about that later.

## About the template

Before this, I used another template. But the RSS & SEO were not set up automatically (?) this one is. I'll look into it some more.

## To Do

- [ ] post 3 new posts
- [ ] change font
- [ ] edit home, give content category navigation
- [ ] make a content collection of my projects
- [ ] trying to make a 2 language blog
- [ ] learn about SEO
- [ ] learn about analytics

## Conclusion

From this website, hopefully I can throw 2-3 birds straight into the air, learn front-end at the same time, learn writing at the same time. And if I continue to develop it, I don't know what this website will become, I think it has great potential for me.
