---
layout: projects
title: Projects
permalink: /projects/
---

{% for post in site.posts %}
  <div>
    <!-- <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span> -->
    <h3>
      <a class="post-link" href="{{ post.url }}">
        {{ post.title }}
      </a>
    </h3>
  </div>
{% endfor %}