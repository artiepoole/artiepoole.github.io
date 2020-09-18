---
layout: landing
permalink: /research/
title: Physics Research
description: A set of posts demonstrating the projects I undertake as part of my academic studies.
image: /assets/img/tiles/research2.jpg
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
        <a class="button scrolly" href="#{{ post.title | replace:' ', '_' }}">{{post.title | slice: 0, 25 }}...</a>
            {% else %}
        <a class="button scrolly" href="#{{ post.title | replace:' ', '_' }}">{{post.title}}</a>
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
        <fullwidth id="{{ post.title | replace:' ', '_' }}">
          <div class="content">
              <div class="inner">
              <header class="major" text-align="center" >
                <h3>{{post.title}}</h3>
              </header>
              {{ content }}
              <ul class="actions">
                <li><a class="button special" href="{{ root_url }}{{ post.url }}">View Separately</a></li>
              </ul>
            </div>
          </div>
        </fullwidth>
    {%endif%}
    {% endfor %}
</fullwidth>


<section id="remarks">
	<div class="inner">
		<header class="major">
			<h2>Thank you for taking an interest.</h2>
		</header>
		<p>If you are interested in further information about any of these projects or are interested in offering me a chance to apply to your comapny, please do not hesitate to contact me using the form below. If you would like to see a summary of my projects and interests, please visit the highlights page using the link below:</p>
		<ul class="actions">
			<li><a href="/highlights/" class="button next"> View Highlights</a></li>
			<li><a href="#banner" class="button scrolly"> Back to top</a></li>
		</ul>
	</div>
</section>