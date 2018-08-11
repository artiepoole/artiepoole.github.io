---
layout: default
---


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
