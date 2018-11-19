---
layout: post
title:  "Implementation of comments and Open Graph"
date:   2018-11-16 22:12:15 +0100
categories: disqus opengraph opg
---
#### Implementation of comments to my blog posts
For comments on my blog posts I chose to use Disqus. It was already built in the Jekyll theme so I needed to just create an account at Disqus, add configuration inside my _config.yml file for the username and Disqus will load as soon as it is on the specified domain: https://github.com/mc222sn/mc222sn.github.io

#### Open Graph, what is it?
Open Graph is a technology that was created by Facebook. When you insert your link on for example Facebook from a blog post, article from newpaper or something else they want a way to get information about what type of image it will load, what type of url, title, description and so forth. 

Example code of the tags that will be placed in the head section of your website:

```HTML5
<html prefix="og: http://ogp.me/ns#">
<head>
<title>The Rock (1996)</title>
<meta property="og:title" content="The Rock" />
<meta property="og:type" content="video.movie" />
<meta property="og:url" content="http://www.imdb.com/title/tt0117500/" />
<meta property="og:image" content="http://ia.media-imdb.com/images/rock.jpg" />
...
</head>
...
</html>
```
