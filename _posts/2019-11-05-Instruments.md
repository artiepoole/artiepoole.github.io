---
layout: post
title: "Instrument Control Package"
date: 2019-11-05 09:00:00
category: code
image: null
permalink: "/projects/instruments/"
---

<div>
    <span class="image right"> 
        {% include image-gallery-first.html folder="assets/img/projects/instruments" %}
    </span>
    <p> In order to expedite experimental prototyping, I wrote a Python package which contains wrappers for interfacing with the instruments I used regularly. This includes lock-in amplifiers, various keithley instruments, oscilloscopes and some custom kit like the switch box, which I helped design and iterate on. Originally only intended for my use, it has since become instrumental in other research groups development of control software. Several GUIs have been developed for more routine experiments. The source code, and various examples of how to use it, are linked below.</p>
    <p> Because of my expertise in this, I was asked to write a guide for using Python to interface with the equipment in the project teaching labs (3rd and 4th year undergraduate labs). Finally, some LEEM analysis scripts by <a href="https://github.com/TAdeJong/">TAdeJong</a> were heavily modified to use them for PEEM analysis instead.</p>
</div>


<ul class="actions">
    <li><a href="https://github.com/stupoole/instruments" class="button next" target="_blank"><icon class="fab fa-github"></icon> Instrument Package </a></li>
    <li><a href="https://github.com/stupoole/instrumentsexamples" class="button next" target="_blank"><icon class="fab fa-github"></icon> Instruments Examples </a></li>
</ul>