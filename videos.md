---
layout: page
title: Videos
permalink: /videos/
description: Watch comedy videos made by Taylor Brown. All videos made in Chicago.
---

<div class="row">

  {% for post in site.posts %}
    <div class="col-sm-6 col-md-6 col-lg-4">
      <a href="{{ post.url }}" style="background-image: url({{ post.thumbnail_image }})" alt="{{ post.title }}" class="thumbnail"><span>{{ post.title }}</span></a>
    </div>
  {% endfor %}

</div><!--row-->