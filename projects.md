<!-- <ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ posts.content }}</a>
    </li>
  {% endfor %}
</ul> -->

---
layout: default
---

<div class="blog-index">  
  {% assign post = site.posts.first %}
  {% assign content = post.content %}
  {% include post_detail.html %}
</div>