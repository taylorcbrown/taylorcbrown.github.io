---
layout: page
title: Videos
permalink: /videos/
description: Watch comedy videos made by Taylor Brown. All videos made in Chicago.
---

<div class="row">

  {% for post in site.posts %}
    <div class="col-sm-6 col-md-6 col-lg-4">
      <figure class="thumbnail">
        <a href="{{ post.url }}">
          <img src="{{ post.thumbnail_image }}" class="img-fluid" alt="{{ post.title }}">
          <figcaption>{{ post.title }}</figcaption> 
        </a>    
      </figure>
    </div>
  {% endfor %}

</div><!--row-->