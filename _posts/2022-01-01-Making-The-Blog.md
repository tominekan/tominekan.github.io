---
layout: post
title: Making this Blog
---

This blog was the culmination of my pure efforts to avoid doing any sort of hard work. I first created this blog in 2021 (Middle-ish?) but it soon fell victim to my lack of willpower. This year it will not be ignored (hopefully?). Anyway, let's get to the technical details of making this website.

**I didnt make it all by myself.**

Being honest, I completely forgot about my abandoned blog until today (yes, January 1st 2022). Deep in my soul, I always knew I was never going to build a blog by myself. There is just too much that could go wrong, and it really doesn't seem worth the effort to debug. The first idea was to use something like Blogger or Wordpress because they both were simple and required less mental oomph than other solutions

**Neither worked.**

![Wordpress vs Blogger picture](https://i.ibb.co/5Th6dfD/Inked-Word-Press-vs-Blogger-Which-one-is-Better.jpg)

The main problem with Wordpress is expenses. I can't afford to pay for a custom domain or a hosting service. Even though services like this are dirt cheap these days, unfortunately, I am poorer than dirt, so paying for anything is not an option. That being said, I loved their idea of installing tools on a custom domain and hosting service to build a website (CMS).

Price being a barrier, I turned to Blogger. Although Blogger handles hosting and domain for free (although you can customize the domain), it comes with it's own price, the lack of customization and overall functionality. Personally, I don't care too much about the lack of customization, so long that everything looks pretty, but with Blogger, things are not pretty (it's ugly as sin). I don't like looking at ugly websites, and I don't want others to see my work on some **ugly**, generic, overused template. It can be generic and overused, just not ugly.

**Jekyll + GitHub for the win**

![Jekyll and Github saved my soul](https://i.ibb.co/6sxr87J/JEKYLL-AND-GITHUB.png)

Worried for my lazy soul, you might queston, "But Tomi, isn't that more work in the end? I mean you have to do all this configuring and stuff with Jekyll and GitHub pages, getting them to work together nicely, uploading your content, and it just sounds like a whole lotta effort." Well, concerned reader, back when I was younger (the 2021s), I was  willing to do more work and actually did all of this setting up before in my abandoned blog. Now all I needed to do was to use what I already have.

Alas, it was not so easy, I didn't want to have to go to the source code, get the current date, rename the title to Jekyll's standards, commit and then push the changes to GitHub. There **had** to be an easier way, and there was (this is the marvelous thing about tech, there is always an easier way), this lifeline came in the form of `jekyll-admin`, which would let me manage my files with an easy to use GUI instead of constantly repeating the long laborious process of updating the blog everytime I wanted to write something.

Again, there were some problems with this idea, `jekyll-admin` seemed to only work with a localhost, and I re-learned the hard way that Jekyll for GitHub pages was not the same thing as the Jekyll on my command line. While Jekyll would not run my current configuration (without modifications, more work on my end), GitHub Pages was having a jolly time with it, executing it flawlessly. Naturally, this posed some problems.

**Lesson to learn?**

Eventually I whipped up a command line script to automate the process. However, I learned something very important, **_work smarter, not harder_**. If I had done just a little bit of research then I would not have set up `jekyll-admin` for GitHub pages, saving me precious time and effort in creating this blog.


