---
layout: page
title: Videos
permalink: /videos/
description: Watch videos made by Taylor Brown. All videos were made in Chicago.
---

{% for post in site.posts %}
  <article class="post">
  	<header class="clearfix">
	    <h2><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h2>
	    <time class="date">{{ post.date | date: "%b. %-d, %Y" }}</time>
    </header>
    {{ post.excerpt }}
  </article>
{% endfor %}
