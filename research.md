---
layout: default
permalink: /research/
---

<top>
	<div class="container">
	<h1> Research Projects</h1>
	<p> Below is a summary of my previous research projects from my time at <a href="https://www.nottingham.ac.uk/physics">The University of Nottingham.</a> To learn more about the Spintronics Group at Nottingham visit <a href="https://nottingham.ac.uk/~ppzgan/spin/">the group's homepage</a> which I maintain.</p>
	</div>
</top>
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
<div class="floating-list">
	<ul>
	  {% for post in site.posts %}
	  {% if post.category == "research" %}
	    <li>
	    	{% if post.title.size > 28 %}
  		<a href="#{{ post.title }}">{{post.title | slice: 0, 25 }}...</a>
	    	{% else %}
		<a href="#{{ post.title }}">{{post.title}}</a>
    		{% endif %}

	    </li>
	  {% endif %}
	  {% endfor %}
	</ul>
</div>	
</div>
</div>

<script src="/js/jquery.min.js"></script>
{% include text-expand.html %}