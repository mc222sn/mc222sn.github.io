---
layout: post
title:  "My take on CSS Preprocessors and SSG"
date:   2018-11-16 22:11:15 +0100
categories: css ssg csspreprocessors
---
#### Pre-compling CSS compared to regular CSS
I think pre-compiling CSS compared to regular CSS is that it's really effective. You can organize the code much better, it's better when the code is to be maintained by another person later on and it's quicker to edit many elements at the same time with variables without to go through all the code inside the regular .css file. The technique I was using is SASS.

You could of course just use the tools in your IDE to replace all those elements, but if you have variables you could do other calculations as well. Let's say we want to store a value of a width size for some elements, `$base-width = 400px` and then we have another element that should be half the size of the `$base-width`. We could just use it like this: `$base-width / 2` and we get 200px for that element. Very simple!

The downside of it that I can think of is when I'm using the browser debug tool and want to find a specific element it could take time to find it in the sass files.

#### Static Site Generators
My impressions of SSG (Static Site Generators) are really good. It's really fast to create a site, easy to understand how it works and many tools already built in. 

So what type of projects are they suitable for then? Well I would say it's a good choice for documentation sites. For example a documentation site for an Free Software/Open Source project or just a simple blog. Or both. 

#### Implementation of comments to my blog posts

#### Open Graph, what is it?
