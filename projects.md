---
layout: landing
permalink: /projects/
title: Design Projects
landing-title: 'Personal Projects'
description: A set of posts demonstrating the projects I undertake outside of work.
image: /assets/img/tiles/projects.png
author: Stu Poole
nav-menu: true
show_tile: true
---

<section id="one" class="spotlights">
	<div class="inner">
		<header class="major">
			<h2>Contents</h2>
		</header>
        <ul class="actions">
        {% for post in site.posts %}
        {% if post.category == "project" %}
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
</section>was 

<!-- This code loads all posts and displays them -->
<!-- Two -->
<fullwidth id="two" class="spotlights">
    {% for post in site.posts %}
    {% if post.category == "project" %}
      {% assign content = post.content %}
      {% include post_detail.html %}
    {%endif%}
    {% endfor %}
</fullwidth>
