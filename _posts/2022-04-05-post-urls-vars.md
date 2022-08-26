---
layout: post
title: Post URLS vars
author: Lfrakie
categories: [ News ]
image: "/uploads/prtscr-capture_79.jpg"
tags: []


---
Practice post

site url:
{{site.url}}

page url:
{{page.url}}

site baseurl:
{{site.baseurl}}

page title:
{{page.title}}

replace - page url name:
{{page.title | replace: " ", "-"}}


base URL:
{{ site.baseurl }}



<a href="{{site.baseurl}}{{page.url}}index.html" download="{{page.title | replace: " ", "-"}}.odt.html">Download Text</a>


