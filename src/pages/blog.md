---
layout: blog.njk
metaDescription: A sample Blog page listing various posts.
date: 2017-01-01
permalink: blog{% if pagination.pageNumber > 0 %}/page/{{ pagination.pageNumber
  }}{% endif %}/index.html
subtitle: A collection of technical blog posts and random thoughts
title: Look at me
eleventyNavigation:
  key: Blog
  order: 5
pagination:
  data: collections.post
  size: 20
---
A test post.

![A relief map of the US](/src/assets/img/us-map.jpg "A US map")