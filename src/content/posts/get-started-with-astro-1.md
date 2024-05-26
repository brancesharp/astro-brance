---
title: 'Setting up your first Astro Project'
pubDate: 2024-05-19
description: 'Building a website with Astro for total beginners - Part 1'
author: 'Brance Sharp'
tags: ["tech"]
---

### Why Astro?
Over the past few weeks I've been diving into several JavaScript frameworks with the goal of finding something that is
conceptually simple and provides a smooth developer experience. Astro happened to be one of the first options I
tried, and it didn't take long for me to notice that it checked all of the boxes I cared about.

For context, I have some some experience with Python and Go, but I haven't dived too deep into JavaScript and I'm just
dipping my toes into web development. Despite this, I found Astro incredibly easy to get started with and build a website
with.

Astro has several advantages over other JavaScript frameworks, especially for simple use cases like blogs or portfolio sites:
- It's much simpler to use and get started with.
- It's beginner friendly, especially if you are not entirely comfortable with JavaScript/TypeScript.
- It's flexible enough to grow with you, even if your project needs change over time.

Building with Astro is fairly straightforward, provided you have some HTML, CSS, and JavaScript knowledge. Again, you don't need be 
an expert to get started, but some experience with these will make the process here smoother. 

This blog post will walk you through the beginning steps of building a website with Astro. We'll be leaning heavily on Astro's
pre-built templates to get us started quickly, but with some additional tuning you can really make it your own.

### Initializing a new project
First, you'll need to have a JavaScript runtime environment installed on your computer. I'll be using Node.js, but you can use Bun if 
you'd prefer. The steps to initialize the project will be similar with either.

If you are not sure if you have Node installed, you can check with the following command on your terminal:

```bash
node -v
```

You'll want at least version v.20.3.0 of Node.js installed. If you don't have Node installed, you can download it 
[here](https://nodejs.org/en).

Next, type the following command into your terminal. This will initialize a new Astro project, and give you several options for 
scaffolding your project.

```bash
npm create astro@latest
```

You'll be prompted to make several selections which will determine the default setup for your project. First, you'll need to name 
the directory where your project will live. Type the following into your terminal:

```bash
./blog-example
```

Go ahead and make the following selections to finish up:
```
How would you like to start your new project?
- Use blog template

Do you plan to write TypeScript?
- Yes

How strict shold TypeScript be?
- Strict

Install dependencies? (recoomended)
- Yes

Initialize a new git repository?
- No
```

A new folder will be created with the name `blog-example`. This folder will contain all of files we need to get started.

In the next post, we'll explore the folders and files that we just created, and discuss how they'll be used to set up your new 
website.