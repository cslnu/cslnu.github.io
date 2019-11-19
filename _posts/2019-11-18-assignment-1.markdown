---
layout: post
title:  "Assignment 1"
date:   2019-11-18
categories: jekyll update
image: /pics/icon_small.png
type: blog
---
### Brace yourselves, text is coming!

## Pre-compiled CSS
Pre-compiled CSS or CSS preprocessors is amazing. When using a CSS preprocessor you are not only going to get rid of gigantic CSS files in which you probably would need a torch and a map in order to find your treasure, but you can also make use of variables.

A CSS preprocessor compiles something calles SCSS files, and these files works just as a normal CSS file but with the extension that you can write your layouts and design in modules rather than group all of it into a big CSS pile. The CSS preprocessor grabs all these SCSS modules that you create and produces a regular CSS file which contains the design elements that you have set up. Within these SCSS files you can also make us of variables in your elements, this makes it easy to stick to a certain color scheme since you could just create a specific variable for colors, or fonts, or font sizes. The only thing that limits you is your imagination. Kind of.

On this website I made use of a CSS pre-compiler called SASS, simply because it was imbedded in the Jekyll template used.

## SSG
The way a static site generator (SSG) work is by compiling different templates that you set up for your code. This means that you could set up a template for your header, body, footer, and all kinds of things. This makes editing of your code quite easy, seeing that you would only have to change within your templates instead of going through each .html file in your directory and manually change the code you want to change.

SSG's should preferably be used for websites that does not need a very dynamic environment, so for blogging it's prefect!

Static site generators are know to be a quick way to launch a website, and it is if you know what you are doing. As a novice I had quite the challenge getting this site up and running since I had no prior experience with Jekyll. So I would probably not recommend using Jekyll if you're under time pressure to launch a static site, unless you have someone that you can ask for help. But then again, I think I would recommend it, because once you get the hang of it it's quite smooth sailing.

## Humans vs Robots
In order to index all the sites available on the internet bigger search engines makes use of something called Robots. These robots scan websites in order to index their content and make it easier to find through search engines. 

Other parties might use these robots in order to collect email addresses which inboxes they can fill with spam emails. In order to prevent this there is something called a robots.txt file that you can include in your root folder in your website. This file tells these robots, who might not even bother with reading the robots.txt file, if it is OK to either index the website or search it for useful information.

They way this works is that before one of these robots access any of a website's html files it searches for the robots.txt file. In this document you can specify what content the robot should have access to, if any. This website exludes all kind of activity from robots, they are "denied" entry. 

And on the other hand we have something called a humans.txt file. This file is used to present the people behind the website, its creators. This file presents those who made the website and might contain other information such as a "Thank you!" to some parties. If you take a look at this website's humans.txt file you'll see that I refrained from adding myself as a creator since it might not be the best thing I've ever created, but atleast I have LNU some thanks for giving me the chance of making it!

## Disqus
The way I chose to implement comments on this blog was by signing up with Disqus and use their platform.
They offered a pretty simple solution which seem to be quite easy to use and to understand.

## Open Graph
Open graph is a markup protocol that makes use of meta tags within your HTML code to present your website in a representative manner. When posting your websites url in a social media post or comment your link will produce a short preview of the website or what ever section you chose to link towards. This presentation can contain anything from a small thumbnail to a video with corresponding text related to the url and what kind of website it is.

This website provides an image, the url, the title of what's being shared and what kind of material it is that is being shared a.k.a the "type" of content.