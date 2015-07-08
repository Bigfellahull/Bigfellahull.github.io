---
layout:     post
title:      "I want to be an old school programmer"
subtitle:   "starting my journey with C++."
date:       2015-07-08 20:00:00
author:     "James Hull"
header-img: "img/old-school-programmer-bg.jpg"
---

<p>Now old school is relative. For me, whilst I did some minimal embedded C during my university days writing controllers for robots (yes robots are cool) most of my time was spent coding with Java and C#.</p>

<p>Now I love C#. My day is spent writing C# websites and APIs and it's a fantastic language. However a part of me recently has wanted to join the nowadays elusive club of old school C and C++ programmers. So I decided to devote what little free time I have to accustoming myself with C++.</p>

<p>I fired up my browser and visited everybody's favourite search engine and tapped in "learn C++". I immediately realised this was a bad idea. I'm a programmer. I know how to program. I know about pointers and references, operators, functions, inheritance etc. So I looked for something a little more intermediate in level. I didn't have much luck.</p>

<p>I'm the kind of person who likes to jump right into the deep end and paddle for dear life. So the best thing for me to do was decide on something to make and just do it. In C++. How hard could it be?</p>

<p>I love games. Who doesn't. I've meddled in some simple game making with C#. I was all over XNA when it was around. So a game seemed a sensible project. Obviously something small and easy to just test the waters. I came across a <a href="http://gamedevelopment.tutsplus.com/tutorials/make-a-neon-vector-shooter-in-xna-basic-gameplay--gamedev-9859">tutorial series</a> on Tuts+ network building a 2D top down shooter - Geometry Wars style in XNA. Perfect. I'm familiar with XNA, so why not port this to C++?</p>

<h2 class="section-heading">The journey begins</h2>

<p>I fired up Visual Studio and away I went. Now, seeing as the tutorial was XNA and I wanted this to be a real simple introduction to C++, I made the decision to use the <a href="https://github.com/Microsoft/DirectXTK">DirectXTK</a>. It's a collection of helper classes that mimic many of the XNA structures and methods which makes using DirectX much more simple. It has things like SpriteBatch for drawing 2D textures, SimpleMath which hides a lot of the DirectXMath SIMD complexity and a tonne of other features.</p>

<p>Now, the way the guy structure his game and went about things I don't necessarily agree with. But for my first project I decided to keep the port relatively the same. Some parts are different, but it's pretty faithful. I did have some troubles. Coming from a managed background resulted in having some memory issues. Getting out of the mindset to new everything up is hard. But after some tlc, it seems to work ok. By no means is it good code. Let me just make that clear right now. It's probably shit. But it was a learning experience. Getting a window open and initialising DirectX, getting things on screen, moving about, some simple AI, implementing bloom, was all exciting.</p>

<img src="{{ site.baseurl }}/img/posts/2dShooter-2015-07-08 20-22-31-19.jpg" alt="2D shooter screen shot">
<span class="caption text-muted">The 2D shooter in action.</span>

<p>I didn't get to finish the port. Honestly I got a little bored and it achieved what I wanted it to do which was to just let me play around with the C++ syntax and get my head around some of the bullshit in C++ like headers. Some stuff in C++ really makes you appreciate just how developer friendly (easy) C# is. It also helped me confirm, that I do actually want to continue with this journey of learning C++.</p>

<p>As I've mentioned, this is not an example of how to write C++ code. The code is bad, the project is structured terribly. But hey, it was useful for me. So maybe it's useful to others? I've stuck the code up on GitHub so <a href="https://github.com/Bigfellahull/2dShooter">feel free to peruse</a> and use as you like.

<h2 class="section-heading">How hard can it be?</h2>

<p>Simply porting the code was pretty straight forward. However it did make me realise that there is so much that I don't know. So I've now moved on to something a little more ambitious, complicated and challenging. I am really going to make an effort to try and research how more competent and experienced old school C developers do things and apply their wisdom. I'm now writing my own 2D software renderer to really get an understanding of exactly how my game is spit out onto the screen. Yikes that one is much harder and for future blog posts!</p>

<p>All in all, this was good way to kill some free time over a couple of weeks and I really enjoyed it. There is something about making games that you just don't get when programming other software. I mean, writing a wicked sweet RESTful API, or a slick single page app is pretty cool but compared to controlling a sprite on the screen with my Xbox controller - whilst the controller rumbles in my hand - is pretty fucking awesome. It almost makes you jealous of professional games programmers despite all the horror stories... Almost.</p>

<h2 class="section-heading">TL;DR</h2>

<p>I made a game. It's probably shit. But it was fun, and has encouraged me to continue with my journey or learning C++. <a href="https://github.com/Bigfellahull/2dShooter">Check out the code on GitHub</a>.</p>