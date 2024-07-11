---
layout: landing
title: Highlights
description: null
image: /assets/img/tiles/smiley_display.jpg
author: Stuart Poole
show_tile: true
nav-menu: false
permalink: /highlights/
---

<!-- One -->
<fullwidth id="one" class="spotlights">
    <fullwidth>
        <div class="content">
        <div class="inner">
            <header class="major" text-align="center" >
                <h2>About Me</h2>
            </header>
            <div>
                <span class="image right">
                    <p><img src="{% link /assets/img/tiles/me_top.png %}" alt="" data-position="center center" /></p>
                </span>
                <p> I have a PhD in experimentla physics, specifically in antiferromagnetic spintronics and magnetooptics. Through the PhD, I became an expert in interfacing with equipment using Python and in experimental design. Since then, I have discovered a passion for the interplay between hardware and software and am therefore now striving to immerse myself in just that.</p>
                <p>I have undertaken many personal projects involving mechanical design, electronics and programming in various languages, and I am always jumping into the deep end to learn new skills. With access to my dad's workshop and some tools of my own, I undertake woodworking projects as a hobby and have worked as an assistant to a builder/joiner and renovated houses and built extensions, developing a very board suite of skills and varied understanding of how things work, which have been demonstrated as remarkable applicable to the research and development environment. This page provides a summary of my PhD research, followed by examples of four projects, each primarily showcasing: programming skills, equipment design skills, electronics knowledge and woodworking skills, followed by a bit more about me.</p>
            </div>
        </div>
        </div>
    </fullwidth>
    <!-- Research Highlights>
    <fullwidth>
        <div class="content">
        <div class="inner">
            <header class="major">
                <h2>Research - New Characterisation Techniques for Thin Film Antiferromagnetic Materials </h2>
            </header>
            <div>
                <span class="image left">
                    <img src="{% link /assets/img/tiles/research2.jpg %}" alt="" data-position="center center" />
                    <p class="align-center">Example magneto-optical detection scheme</p>
                    <img src="{% link /assets/img/research/kits_photos/cryostat_bore.jpg %}" alt="" data-position="center center" />
                    <p class="align-center">A view down the bore of a cryostat</p>
                </span>
                <p>
                My PhD research (thesis linked below) consisted of developing new measurement techniques for measuring antiferromagnetism (a form of magnetism in which there is no net magnetisation, although the materials possesses local and long range magnetic ordering) in CuMnAs samples. In theory, antiferromagnetic materials are ideal materials for use in storage devices because they are impervious to external magnetic fields, have very fast switching dynamics and maximum storage density, overcoming limitations in existing magnetic storage devices. Writing of information has been experimentally shown (paper linked below) however these results highlight the main drawback: the readout signals are much weaker (0.1% resistance change compared to 150% recorded in ferromagnet HDDs). My research hoped to find new ways to measure these changes and explore the new ways to measure the magnetic properties of antiferromagnets in order to expedite material development.  
                </p>
                <p>The aforementioned research goals meant that I was exposed to a wide array of experimental techniques (optical, large facility, electronic, cryogenic, vacuum etc.), collaborated internationally (TU Dortmund, several institutes in Prague and with Ioffe Institute back in 2018) and have gained vast experience in interfacing with hardware. For this, I primarily used Python (more about this below), but have also included Arduino devices as intermediate hardware and have programmed a Red Pitaya for a spectroscopic applications. I left the research group just as they discovered a new class of magnetism called altermagnetism. This new material promises even more ideal properties for the next generation of storage devices. I have continued to work with the group to improve experiments and accelerate their research into this new field.
                </p>
                <p> Below, I have included a few other links for the keen reader, focussing on CuMnAs, the material I studied.</p>
            </div>
            <ul class="actions">
                <li><a href="/assets/pdfs/Thesis.pdf" target="_blank" class="button"><span class="fas fa-file-pdf"></span>PhD Thesis</a></li> 
                <li><a href="https://www.nature.com/articles/ncomms15434" target="_blank" class="button"><span class="fas fa-link"></span>First Switching Paper</a></li>
                <li><a href="https://aip.scitation.org/doi/10.1063/5.0103390" target="_blank" class="button"><span class="fas fa-link"></span>Neutron Diffraction paper</a></li> 
                <li><a href="https://www.nature.com/articles/nnano.2016.18" target="_blank" class="button"><span class="fas fa-link"></span>AFM Spintronics Review</a></li>
                <li><a href="/research/" class="button next">More Research</a></li>
            </ul>
        </div>
        </div>
    </fullwidth>
    <!-- Code Highlights -->
    <fullwidth>
        <div class="content" id="programming">
        <div class="inner">
            <header class="major">
                <h2>Instrument Control</h2>
            </header>
            <div>
                <span class="image right">
                    <img src="{% link /assets/img/research/guis/rhs.png%}" alt="" data-position="center center" />
                    <p class="align-center">The ArtieLabUI window</p>
                    <img src="{% link /assets/img/research/guis/switching.png%}" alt="" data-position="center center" />
                    <p class="align-center">An electrical switching GUI</p>
                    <img src="{% link /assets/img/research/guis/ASOPS.png%}" alt="" data-position="center center" />
                    <p class="align-center">A GUI for spectroscopy measurements using ASOPS</p>
                </span>
                <p>I write code as a hobby and like to explore new languages when doing so, but as it stands, I am most skilled in Python. I recently started using C/C++ to improve the performance of existing Python code, especially in image processing, having some experience using standalone C++ to simulate magnetic systems. This is because, throughout my PhD, I wrote Python code to control instruments, process data and for image processing applications. Because of this aptitude, while working as technical specialist in the teaching labs, I was approached by my research group, asking if I would be able to re-write the existing proprietary LabView software which was shipped with their latest system: a magneto-optical Kerr effect (MOKE) microscope set-up. They employed me alongside my technical specialist role and I have developed <a href="https://github.com/stupoole/SpintronicsMOKE">ArtieLabUI</a> an open-source replacement which is faster, editable by the group. It was developed specifically for their application and with their input throughout. At over 5000 lines of Python (and 100 of C++), this is my largest project yet. This required real-time image processing, multithreading, C++ interfacing in Python, UI design and a lot of reverse engineering.</p>
                <p> Also for work, I wrote a Python package which contains wrappers for interfacing with the instruments I used regularly. This, and some examples, are included below as well. Because of my expertise in this, I was asked to write a guide for using Python to interface with the equipment in the project teaching labs (3rd and 4th year undergraduate labs). Finally, some LEEM analysis scripts by <a href="https://github.com/TAdeJong/">TAdeJong</a> were heavily modified to use them for PEEM analysis instead. </p>
                <p>As a hobby a while ago, my brother and I started writing a game engine in Kotlin, called Balding Gate. Although functional as a world editor and playable scenarios, we shelved development when we heard tell of Baldur's Gate 3. Aside from this, I have won two Hackathons for remote controlled robots, won a pebble smartwatch for developing an app for it and have attended other hackathons and game jams.</p>
                <p> Other snippets of code and other projects have been lost or are not publically available for various reasons. These include my time evolving 3D magnetic simulation, simple Arduino scripts and the Red Pitaya code. </p>
            </div>
            <ul class="actions">
                <li><a href="https://github.com/stupoole/SpitnronicsMOKE" class="button next"> MOKE GUI </a></li>
                <li><a href="https://github.com/stupoole/instruments" class="button"><icon class="fab fa-github"></icon> Instrument Package </a></li>
                <li><a href="https://github.com/stupoole/instrumentsexamples" class="button"><icon class="fab fa-github"></icon> Instruments Examples </a></li>
                <li><a href="/code/balding gate/" class="button next">More on Balding Gate</a></li>
                <li><a href="/code/" class="button">More programming projects</a></li>
            </ul>
        </div>
        </div>
    </fullwidth>
    <!-- ArtOS -->
    <fullwidth>
        <div class="content" id="os">
        <div class="inner">
            <header class="major">
                <h2>OS Development</h2>
            </header>
            <div>
                <span class="image left">
                    <img src="{% link assets/img/projects/ArtOS/keyboard_support.gif%}" alt="" data-position="center center" />
                    <p class="align-center">ArtOS Test</p>
                </span>
                <p></p>
            </div>
            <ul class="actions">
                <li><a href="https://github.com/stupoole/artos" class="button next"> ArtOS</a></li>
                <li><a href="https://github.com/stupoole/stupoole.github.io" class="button next">This Website</a></li>
                <li><a href="/code/" class="button">More programming projects</a></li>
            </ul>
        </div>
        </div>
    </fullwidth>
    <!-- RTS -->
    <fullwidth>
        <div class="content" id="RTS">
        <div class="inner">
            <header class="major">
                <h2>Equipment Design</h2>
            </header>
            <div>
                <span class="image right"> 
                    <div class="ratio-square"> <iframe class="ratio-inner" title="Peltier Controlled Vacuum System - Exploded View" allowfullscreen mozallowfullscreen="true" webkitallowfullscreen="true" allow="autoplay; fullscreen; xr-spatial-tracking" xr-spatial-tracking execution-while-out-of-viewport execution-while-not-rendered web-share src="https://sketchfab.com/models/7c1241b2a7914d39afcc135100ca44ca/embed"> </iframe> <p style="font-size: 13px; font-weight: normal; margin: 5px; color: #FFFFFF;"></p></div>
                    <p class="align-center">3D model of the room temperature vacuum system</p>
                </span>
                <p>I have drawn many individual parts in CAD, and made several larger assemblies. Several of the smaller parts have been 3D printed, such as a replacement handle for a Black and Decker workmate workbench and a controller for an Atari 8-bit computer from the '80s. In many of my projects you can see evidence of CAD and progression in skills using it. Recently I have focussed on learning best practices and trying to form good habits. For the following project, I drew a CAD model in the final size and had it manufactured by the in-house workshop at UoN and LewVac.</p>
                <p> As an example of my design skills, I present my room temperature system: I was tasked with designing a high vacuum system with stable temperature control for measuring electrical devices at and near to room temperature for the Spintronics group. The stability is required to eliminate drift in resistance measurements and to cool the sample when under load. There were three main points in the brief:
                <ul>
                    <li>The temperature of the sample space has to remain within 0.1°C of the set point which can be anywhere between 0°C and 50°C.</li>
                    <li>The sample, mounted to a 12 pin circular header, must be in high vacuum (10<sup>-5</sup> mBar) and have good thermal contact with the sample space with minimal thermal lag to the temperature control mechanism.</li>
                    <li>The measurement wires should be shielded from electrical noise.</li>
                </ul>
                It turns out that we achieve:
                <ul>
                    <li> Temperature stability within 0.005°C in a range from -10 to 60°C.</li>
                    <li>The vacuum reaches (10<sup>-8</sup> mBar) and the thermal lag is less than a minute from Peltier to sample, with no drift in temperature throughout measurement</li>
                    <li>The crosstalk is not noticeable as larger than usual measurement noise.</li>
                </ul>
                I designed the vacuum chamber, heatsink and control box and then wrote a custom python interface for the control box to hide a lot of the dangerous settings available in the proprietary software for the temperature controller supplier. A Peltier device was chosen as the temperature control mechanism because it can be used to both heat and cool the sample space. Click the link below to find out why this made the design so challenging and to learn more about the system's applications. A scientific paper describing the key features and operating parameters is in preparation.
                </p>
            </div>
            <ul class="actions">
                <li><a href="https://arxiv.org/abs/2403.03745" class="button" target="_blank"><icon class="fab fa-file-pdf"></icon> Published Journal Article</a></li>
                <li><a href="/projects/#Room_Temperature_System" target="_blank" class="button next">More on the RTS</a></li>
                <li><a href="/projects/" class="button" target="_blank">See more projects</a></li>
            </ul>
        </div>
        </div>
    </fullwidth>
    <!-- Crokinole Board -->
    <fullwidth>
        <div class="content">
        <div class="inner">
            <header class="major">
                <h2>Woodwork and DIY</h2>
            </header>
            <div>
                <span class="image left">
                    <img src="{% link /assets/img/tiles/crokinole.jpg %}" alt="" data-position="center center" />
                    <p class="align-center">Crokinole Board, Discs and Bowl</p>
                </span>
                <p>I really like to make things (as if that wasn't already clear) and one of the easiest materials to get started with is wood because the materials are readily available, and it is possible to do a lot of things with few expensive tools (by using hand tools). It is for this reason that most of my projects are woodworking, not because it is my favourite. To get where I am now, I learned most of what I know from my dad but also worked as a joiner's labourer during many of my undergraduate holidays. Recently I have been working on earrings to hone my skills with hand tools. When I head home to visit my parents. Over a Christmas break, my dad and I made a <a href="/projects/#Crokinole_Board" target="_blank">crokinole board</a> (a tabletop game somewhere between curling/boules and pool with DNA from shuffleboard and air hockey) to play with family and friends. The following year we made a <a href="/projects/#Chess_Board" target="_blank">chess board</a>. It is always a joy to have access to his tools, knowledge and company.</p>
            </div>
            <ul class="actions">
                <li><a href="/projects/#Crokinole_Board" target="_blank" class="button next">More on Crokinole</a></li>
                <li><a href="/projects/#Chess_Board" target="_blank" class="button next">More on the Chess Board</a></li>
                <li><a href="/projects/" target="_blank" class="button">See More Projects</a></li>
            </ul>
        </div>
        </div>
    </fullwidth>
    <!-- Electronics -->
    <fullwidth>
        <div class="content" id="electronics">
        <div class="inner">
            <header class="major">
                <h2>Electronics</h2>
            </header>
            <div>
                <span class="image right">
                    <img src="{% link /assets/img/projects/2WireLEDDriver/01 - Finished, lid off.jpg %}" alt="" data-position="center center" />
                    <p class="align-center">Assembled dimmable 2-wire LED driver.</p>
                </span>
                <p>I have undertaken many small electronics projects, such as replacing a power supply in an old BBC Master computer, making cables or analogue filters for laser experiments and the box for the temperature controller in the RT system. The two other largest projects are a cartridge emulator for Atari 8-bit series computers using, an Arduino Mega, with plans to replace it with a PIC after the proof of concept stage, and a display board demonstrating the function of an 8-bit adder for outreach purposes. I have also focused on hardware-software interfacing in programming for my research and in my contribution to hackathon entries (see <a class="scrolly" href="#programming">Programming</a> for more on hackathons) but I helped with all the circuitry in those projects (where applicable). My most impressive electronics project is the following LED driver.</p>
                <p>Two-wire LED drivers work by oscillating the polarity of a driving DC current applied to a string of LEDs with sections of opposing polarity LEDs. This allows for easy assembly and control of the LEDs for animations etc. for Christmas lights. Typically, the controllers come programmed with several fun animations however they were all too bright and I just wanted adjustable soft lighting. I wanted to make a simple dimmable LED string driver for a 2-wire LED chain. As always, things got out of hand and the project ended up quite sophisticated. See the image on the right for a sneak-peak and click below to find out more.</p>
            </div>
            <ul class="actions">
                <li><a href="/projects/2WireLEDDriver/" target="_blank" class="button next">More on LED Driver</a></li>
                <li><a href="/projects/" target="_blank" class="button">See more projects</a></li>
            </ul>
        </div>
        </div>
    </fullwidth>
    <!-- Conclusion -->
    <fullwidth>
        <div class="content">
        <div class="inner">
            <header class="major">
                <h2>What makes me tick</h2>
            </header>
            <div>
                <span class="image left">
                    <img src="{% link /assets/img/tiles/me.png %}" alt="" data-position="center center" />
                    <p class="align-center"></p>
                </span> 
                <p>I hope you found my projects interesting and have learned something from them! If you're wondering what kind of person I am, and how I find time for these alongside my studies and life, you'll be glad to hear that I have a healthy work-life balance, with a less healthy interests in specialty coffee and rock climbing (indoors and out), finding time to cook and eat world foods, play board games and video games, socialise with friends, listen to a lot (and I mean a lot) of different music, read books (sci-fi and fantasy novels lately), and go on adventures: hiking in the woods, hiking up mountains, climbing up rock faces and exploring new cities. When not being active, I spend my time watching educational YouTube, often in niche subjects e.g. organic chemistry syntheses, machining and botany, but also in more typical subjects. </p>
            </div>
        </div>
        </div>
    </fullwidth>
    <!-- interest -->
    <fullwidth background-color="#2e3450">
        <div class="content">
        <div class="inner">
            <header class="major">
                <h2>Thank you for taking an interest</h2>
            </header>
            <div>
            <p>If you are wanting further information about any of these projects or are considering offering me a chance to apply to work at your company, please do not hesitate to contact me using the form below.</p>
            </div>
            <ul class="actions">
                <li><a href="#contact" class="button scrolly">Contact me</a></li>
                <li><a href="/about/" class="button next">More about me</a></li>
            </ul>
            <ul class="actions">
                <li><a href="#banner" class="button special scrolly">Back to top</a></li>
            </ul>
        </div>
        </div>
    </fullwidth>
</fullwidth>
