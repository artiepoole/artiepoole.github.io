---
layout: default
---

<!-- This code loads all posts and displays them -->

<div class="blog-index span1">
	<ul>
	  {% for post in site.posts %}
	    <li>
	      {% assign content = post.content %}
	      {% include post_detail.html %}
	    </li>
	  {% endfor %}
	</ul>
</div>	


<!-- This is the code for the list of posts that should scroll with the page eventually -->

<div class="blog-index span2">
	<ul>
	  {% for post in site.posts %}
	    <li>
	      <a href="{{ post.url }}">{{ post.title }}</a>
	    </li>
	  {% endfor %}
	</ul>
</div>	


