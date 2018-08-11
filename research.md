---
layout: default
---

<!-- This code loads all posts and displays them -->

<div class="row">
<div class="span1">
	<ul>
	  {% for post in site.posts %}
	  	  {% if post.category == "research" %}
	    <li>
	      {% assign content = post.content %}
	      {% include post_detail.html %}
	    </li>
	    {%endif%}
	  {% endfor %}
	</ul>
</div>	

<div class="span2">
	<ul>
	  {% for post in site.posts %}
	  {% if post.category == "research" %}
	    <li>
	      <a href="#{{ post.title }}"> {{post.title}} </a>
	    </li>
	  {% endif %}
	  {% endfor %}
	</ul>
</div>	
</div>

