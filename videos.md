---
layout: page
title: Videos
permalink: /videos/
description: Watch comedy videos made by Taylor Brown. All videos made in Chicago.
---

<div class="row">
  {% for post in site.posts %}
    <div class="col-md-4">
      <a href="{{ post.url }}" class="thumbnail"><img src="{{ post.thumbnail_image }}" alt="{{ post.title }}" class="img-fluid"></a>
    </div>
  {% endfor %}
</div><!--row-->