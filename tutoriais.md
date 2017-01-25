---
layout: page
title: Tutoriais
published: true
---
<div class="related">
  <ul class="related-posts">
    {% for post in site.posts %}
      <li>
        <h3>
          <a href="{{ post.url }}">
            {{ post.title }}
            <small>{{ post.date | date: "%d/%m/%Y" }}</small>
          </a>
        </h3>
      </li>
    {% endfor %}
  </ul>
</div>
