---
layout: default
title: Home
---

{% for post in paginator.posts %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}

<nav class="pagination">
  {% if paginator.previous_page %}
    <a href="{{ paginator.previous_page_path }}">← Prev</a>
  {% endif %}

  <span>Page {{ paginator.page }} / {{ paginator.total_pages }}</span>

  {% if paginator.next_page %}
    <a href="{{ paginator.next_page_path }}">Next →</a>
  {% endif %}
</nav>