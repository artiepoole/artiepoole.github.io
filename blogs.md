---
layout: default
permalink: /blog/
---

<top>
	<div class="container">
	<h1> Blog Posts</h1>
	<p> This is where I show off my material possessions and discuss anything I thought was interesting, upsetting (read: aggravating) or cool. I'll probably talk about speakers, mechanical keyboards, pens and inks and assorted consumer electronics.</p>
	</div>
</top>
<div class="row">
<div class="span1">
	<ul>
	  {% for post in site.posts %}
	  	  {% if post.category == "blog" %}
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
	  {% if post.category == "blog" %}
	    <li>
	      <a href="#{{ post.title }}"> {{post.title}} </a>
	    </li>
	  {% endif %}
	  {% endfor %}
	</ul>
</div>	
</div>
