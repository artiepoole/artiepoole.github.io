---
layout: landing
permalink: /research/
title: Physics Research
description: A set of posts demonstrating the projects I undertake as part of my academic studies.
image: /assets/img/tiles/research.jpg
author: Stu Poole
show_tile: true
nav-menu: true
---

<!-- This code and adds a button link to the contents page for posts about to be loaded.-->
<section id="one" class="spotlights">
	<div class="inner">
		<header class="major">
			<h2>Contents</h2>
		</header>
        <ul class="actions">
        {% for post in site.posts %}
        {% if post.category == "research" %}
        <li margin-bottom=22>
            {% if post.title.size > 28 %}
        <a class="button" href="#{{ post.title }}">{{post.title | slice: 0, 25 }}...</a>
            {% else %}
        <a class="button" href="#{{ post.title }}">{{post.title}}</a>
            {% endif %}
        </li>
        {% endif %}
        {% endfor %}
        </ul>
	</div>
</section>

<!-- This code loads all posts and displays them -->
<!-- Two -->
<fullwidth id="two" class="spotlights">
    {% for post in site.posts %}
    {% if post.category == "research" %}
      {% assign content = post.content %}
      {% include post_detail.html %}
    {%endif%}
    {% endfor %}
</fullwidth>