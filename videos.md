---
layout: page
title: Videos
permalink: /videos/
description: Watch comedy videos made by Taylor Brown. All videos made in Chicago.
---

<div class="row">
  
  {% for post in site.posts %}
    <div class="col-sm-4">
      <figure class="figure thumbnail">
        <a href="{{post.url}}">
          <img src="{{post.thumbnail_image}}" class="figure-img img-fluid" alt="{{ post.title }}">
          <figcaption class="figure-caption">{{ post.title }}</figcaption>
        </a>
      </figure>
    </div>
  {% endfor %}
</div><!--row-->