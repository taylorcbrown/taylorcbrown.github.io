---
layout: page
title: Videos
permalink: /videos/
---

{% for post in site.posts %}
  <article class="post">
  	<header class="clearfix">
	    <h2 class="pull-left"><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h2>
	    <time class="pull-right date">{{ post.date | date: "%b. %-d, %Y" }}</time>
    </header>
    {{ post.excerpt }}
  </article>
{% endfor %}
