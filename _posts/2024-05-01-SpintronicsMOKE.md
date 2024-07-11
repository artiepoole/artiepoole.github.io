---
layout: post
title: "ArtieLabUI"
date: 2024-05-01 16:00:00
category: code
image: assets/img/research/guis/rhs.png
permalink: "/code/ArtieLAB/"
---

<div>
    <span class="image right"> 
        {% include image-gallery-first.html folder="assets/img/projects/MOKE" %}
        <p class="align-center">ArtieLAB main GUI</p>
    </span>
    <p>Throughout my PhD, I wrote Python code to control instruments, process data and for image processing applications. Because of this experience I was approached by my research group while working as technical specialist in the teaching labs. They tasked me with re-writing the existing proprietary LabView software which was shipped with their latest system: a magneto-optical Kerr effect (MOKE) microscope set-up. They employed me alongside my technical specialist role. The result is <a href="https://github.com/stupoole/SpintronicsMOKE">ArtieLabUI</a>, an open-source replacement which is faster, and modifiable by the group. It was developed specifically for their application and with their input throughout. At over 5000 lines of Python (and 100 of C++), this is my largest project yet. This required real-time image processing, multithreading, C++ interfacing in Python, UI design and a lot of reverse engineering.</p>
</div>

<ul class="actions">
    <li><a class="button" target="_blank" href="https://github.com/stupoole/SpintronicsMOKE"><span class="fab fa-github"></span> View on GitHub</a></li>
</ul>