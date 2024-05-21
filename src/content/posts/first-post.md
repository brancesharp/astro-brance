---
title: 'Setting up an Astro Project'
pubDate: 2024-05-19
description: 'Building a website with Astro for total beginners - Part 1'
author: 'Brance Sharp'
tags: ["astro", "blogging"]
---

### Why Astro?
If you're looking to build a simple, content-driven site, it would be hard to find a better choice than Astro.

You could, of course, build your site with a platform like SquareSpace or Wix. Both are great choices - but these solutions lack the
flexibility and control you gain by building your own site. 

Building with Astro is fairly straightforward, provided you have some HTML, CSS, and JavaScript knowledge. You don't need be an expert
to get started, but some experience with these will make the process here much smoother. 

This blog post will walk you through the beginning steps of building a website with Astro. We'll be leaning heavily on Astro's
pre-built templates to get us started quickly, but with some additional tweaking, you can take it much further.

### Initializing a new project
Alright, first things first: you'll need to have a JavaScript runtime environment installed on your computer. I'll be using Node.js,
but you can use Bun if you'd prefer. The steps to initialize the project will be similar with either.

If you are not sure if you have Node installed, you can check with the following command on your terminal:

```bash
node -v
```

If you don't have Node installed, you can download it [here](https://nodejs.org/en).

Next, type the following command into your terminal. This will initialize a new Astro project, and give you several options for scaffolding
your website.

```bash
npm create astro@latest
```

You'll be prompted to make several selections which will determine the default setup for your project. Go ahead and choose 
the following selections: