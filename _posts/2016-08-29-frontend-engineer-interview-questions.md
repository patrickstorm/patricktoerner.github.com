---
layout: post
title: Frontend Engineer Interview Questions and Answers
description: "Dozens of Frontend Engineer interview questions, and my feeble attempts to answer them!"
tags: []
image:
  feature: abstract-2.jpg
---

I found a big set of [interview questions for frontend engineers](https://github.com/h5bp/Front-end-Developer-Interview-Questions) and decided to answer them. Here we go:

{::options parse_block_html="true" /}
<div class="notice">
# Table of Contents
* [General Questions](#general-questions)
* [HTML Questions](#html-questions)
* [CSS Questions](#css-questions)
* [Javascript Questions](#javascript-questions)
* [Testing Questions](#testing-questions)
* [Performance Questions](#performance-questions)
* [Network Questions](#network-questions)
* [Coding Questions](#coding-questions)
* [Fun Questions](#fun-questions)
</div>

--------

# General Questions

### 1. What did you learn yesterday/this week?

* Well, it's monday morning, so what did I learn this weekend? This weekend I was working on an [Angular](https://angularjs.org/) app with a custom built [CKEditor](http://ckeditor.com/) plugin for a client. Most of it was pretty standard stuff. I suppose what I did the most Googling about what detecting copy/paste events and manipulating copied data across browsers. Due to the potential security vulnerabilities of allowing free access to the clipboard, each browser handles it a little bit differently. Not the most straight forward stuff!

### 2. What excites or interests you about coding?

* Oh man, so much! First, code gives me the power to multiply output tenfold, even hundredfold. Does a task repeat, or is it standardized, in any way? I can speed up how fast you can do that task. Second, it allows me to build what comes to my head. If I have an idea for something, a few hours later, I can have a basic prototype up and running. Third, it empowers me to solve problems, my own and the problems of others. I hate fumbling for keys to unlock my door (first world problems, am I right?) I can get a Raspberry Pi, a few sensors, and code a lock that unlocks itself if I whistle The Andy Griffith Show theme song. If that is empowerment, I don't know what it. Note: I haven't built that whistle lock yet, but it is on my todo list.

# HTML Questions

### 1. What does a doctype do?

* It lets the browser know what version of HTML the code is written with. It tells the browser to render in standard mode, otherwise it will render in quirks mode. Basically it is for legacy reasons. In the end, you just gotta include it.

### 2. What's the difference between standards mode and quirks mode?

* Ah, convenient time to ask. In standard mode, the browser renders the page just how you would expect. It renders it up to the specifications of the w3 web standards. In quirks mode, browsers render the page not up to those specifications. Developers used to account for all of the weird idiosyncrasies of different browsers, so quirks mode attempts to keep those pages working.

# CSS Questions

### 1. What is the difference between classes and ID's in CSS?

* Classes are a little more general. They can be used on multiple elements, and one elements can have multiple classes. This allows you to **consistently** style multiple elements. IDs, on the other hand, should represent exactly one element on the page. IDs take css precedence over classes.

### 3. What's the difference between "resetting" and "normalizing" CSS? Which would you choose, and why?

* Dang it, I had to Google this one. Resetting, essentially undoes all browser default styles. It is then up to the user to style everything. Normalizing makes the default styles consistent across browsers. I do not see much of a use for "resetting" since "normalizing" became a possibility. Many default browser styles are just fine, why mess with success?

# Javascript Questions

### 1. Explain event delegation

* Yes, sir! I decided to break this out into its own post: [Explain event delegation](/explain-event-delegation-javascript/)

### Explain how *this* works

* 

# Testing Questions

# Performance Questions

# Network Questions

# Coding Questions

# Fun Questions