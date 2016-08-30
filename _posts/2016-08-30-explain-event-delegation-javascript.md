---
layout: post
title: Explain Event Delegation - Javascript
description: "Event delegation is easier than you think."
tags: []
image:
  feature: abstract-3.jpg
---

I was working my way through the [frontend engineer interview questions](/frontend-engineer-interview-questions/) and came across this guy:

> Explain event delegation

My first instict is to be offended by how commanding the question was phrased, but I pushed it aside and decided to answer it. Since I thought it would be better as it's own post, here we are.

So, first things first. Imagine event delegation never existed. We have a `ul` with six `li`s in it. Each one needs to alert you of its `id` when clicked on. This is how it could be done:

<p data-height="315" data-theme-id="0" data-slug-hash="rrBaKP" data-default-tab="js,result" data-user="patricktoerner" data-embed-version="2" class="codepen">See the Pen <a href="http://codepen.io/patricktoerner/pen/rrBaKP/">rrBaKP</a> by Patrick (<a href="http://codepen.io/patricktoerner">@patricktoerner</a>) on <a href="http://codepen.io">CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>

In the code above, an event listener is added to each li. Six event listeners in total. When one is clicked, the id is `alert`ed at you.

------

With event delegation, you instead add a listener to the parent. The event will "bubble" up from the li and you can deduce which element was clicked on by examining the event's target attribute. See the codepen below.

<p data-height="315" data-theme-id="0" data-slug-hash="WGZbaK" data-default-tab="js,result" data-user="patricktoerner" data-embed-version="2" class="codepen">See the Pen <a href="http://codepen.io/patricktoerner/pen/WGZbaK/">Basic event delegation example</a> by Patrick (<a href="http://codepen.io/patricktoerner">@patricktoerner</a>) on <a href="http://codepen.io">CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>

Event delegation is a beautiful thing, especially when you are dealing with something more complicated than the code above!

I hope that helped you understand event delegation!