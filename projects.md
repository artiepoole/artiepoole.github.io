---
layout: default
permalink: /projects/
---

<!-- This code loads all posts and displays them -->
<top>
	<div class="container">
	<h1> Hobbyist Projects</h1>
	<p> This page is a list of projects I have worked on as a hobbyist circuit designer, carpenter, tinkerer and code jockey. </p>
	</div>
</top>
<div class="row">
<div class="span1">
	<ul>
	  {% for post in site.posts %}
	  	  {% if post.category == "project" %}
	    <li>
	      {% assign content = post.content %}
	      {% include post_detail.html %}
	    </li>
	    {%endif%}
	  {% endfor %}
	</ul>
</div>	

<div class="span2">
<div class="floating-list">
	<ul>
	  {% for post in site.posts %}
	  {% if post.category == "project" %}
	    <li>
	      <a href="#{{ post.title }}"> {{post.title | slice: 0, 25}} </a>
	    </li>
	  {% endif %}
	  {% endfor %}
	</ul>
</div>
</div>	
</div>

