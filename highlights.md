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

<!-- Main -->
<div id="main">

<!-- One -->
<section id="one" class="spotlights">
	<div class="inner">
		<header class="major">
			<h2>About Me</h2>
		</header>
		<p> I am a highly practical and well-rounded physicist, having studied antiferromagnetic spintronics and magnetooptics for my PhD (viva pending) at the University of Nottingham. During the PhD, I discovered that working with equipment, setting up new experiments and doing these experiments is far more enjoyable than the more academic aspects of research. Therefore, I am aiming to adopt a role as a technician or to work in equipment/instrument design with the aim of contributing to science in ways I am more suited to. I have undertaken many personal projects involving mechanical design, electronics and code in various programming languages, and I am always willing to jump in the deep end to learn new practical skills. With access to my dad's workshop and some tools of my own, I undertake woodworking projects as a hobby and have worked as an assistant to a builder/joiner and renovated houses and built extensions, developing a very board suite of skills and varied understanding of how things work, which have been demonstrated as remarkable applicable to the laboratory environment, as witnessed by my supervisors. This page provides a summary of my PhD research, followed by examples of four projects, each primarily showcasing: equipment design skills, woodwork, electronics knowledge and programming skills, followed by a bit more about me.</p>
	</div>
</section>

<!-- Two -->
<section id="two" class="spotlights">
    <section>
        <span class="image">
            <img src="{% link /assets/img/tiles/research2.jpg %}" alt="" data-position="center center" />
            <p class="align-center">Example Magneto-optical detection scheme</p>
        </span>
        <div class="content">
            <div class="inner">
                <header class="major">
                    <h3>Research</h3>
                </header>
                <p>I am currently doing an experimental physics PhD at the University of Nottingham, in particular in <a href="https://scholar.google.co.uk/scholar?cluster=9253624752299154943&hl=en">Antiferromagnetic Spintronics</a>. My research can be categorised into three main types of experiment: optical pump probe measurements, magnetoresistive electrical measurements and beamtime experiments (it would also be possible to break down my research into three major aims: to understand spin flop, to improve switching and to understand growth of the samples). For magnetooptical experiments, I use two beams of 80MHz pulses lasting <100fs. One beam is high power to pump a system into an excited state and then a weaker beam is used to probe the resulting physical changes in the sample. Primarily, I used delay line pump probe and asynchronous optical sampling to probe a CuMnAs layer's magnetic state using the Voigt efect. I also measured some acoustic coupling and some elastic constants using these techniques. This project involved international collaboration with TU Dortmund in Germany and Charles University in Prague. The magnetoresistive techniques probe magnetic changes in a sample by monitoring the resistance parallel to the flow of current and by measuring something analogous to the hall voltage perpendicular to the current. This was used to observe spin flop and is how we detect the promising current induced magnetic switching effects in CuMnAs. These experiments involve countless collaborations with leading researchers from around europe such as Academy of Sciences of the Czech Republic, Mainz University in Germany, Charles University in Prague, Regensburg University in Germany and Hitachi Cambridge. The beamtime experiments were primarily conducted in Oxfordshire, at Diamond Light Source and  ISIS Neutron and Muon source. The Diamond experiments involve imaging magnetic domains using XMLD-PEEM or observing magnetic dynamics using time resolved <a>something</a>. Please see the research page which separately describes the theory behind each each experiment and then the methods and setup for each experiment in detail. This page also provides links to learn more.</p>
                <ul class="actions">
                    <li><a href="/research/" class="button next">More Research</a></li>
                </ul>
            </div>
        </div>
    </section>
	<section>
        <span class="image left"> 
        <div class="ratio-square"> <iframe class="ratio-inner" title="Peltier Controlled Vacuum System - Exploded View" allowfullscreen mozallowfullscreen="true" webkitallowfullscreen="true" allow="autoplay; fullscreen; xr-spatial-tracking" xr-spatial-tracking execution-while-out-of-viewport execution-while-not-rendered web-share src="https://sketchfab.com/models/7c1241b2a7914d39afcc135100ca44ca/embed"> </iframe> <p style="font-size: 13px; font-weight: normal; margin: 5px; color: #FFFFFF;"></p></div>
        <p class="align-center">3D model of the room temperature vacuum system</p>
        </span>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Equipment Design</h3>
				</header>
				<p>I have drawn many individual parts in CAD, and made several larger assemblies. Several of the smaller parts have been 3D printed, such as a replacement handle for a Black and Decker workmate workbench and a controller for an Atari 8-bit computer from the '80s. In many of my projects you can see evidence of CAD and progression in skills using it. Recently I have focussed on learning best practices and trying to form good habits. For the following project, I drew a CAD model in the final size and had it manufactured by the in house workshop and LewVac.</p>
				<p> As an example of my design skills, I present my room temperature system: I was tasked with designing a high vacuum, very stable temperature controller for measuring eletrical devices for the Spintronics group in UoN Physics. The stability is required to eliminate drift in resistance measurements and to cool the sample when under load. There were three main points in the brief:
				<ul>
				<li>The temperature of the sample space has to remain within 0.1°C of the set point which can be anywhere between 0°C and 50°C.</li>
				<li>The sample, mounted to a 12 pin circular header, must be in high vacuum (10<sup>-5</sup> mBar) and have good thermal contact with the sample space with minimal thermal lag to the temperature control mechanism.</li>
				<li>The measurement wires should be shielded from electrical noise.</li>
                </ul>
                It turns out that we achieve:
				<ul>
				<li> Temperature stability within 0.005°C in a range from -10 to 60°C.</li>
				<li>The vacuum reaches (10<sup>-8</sup> mBar) and the thermal lag is less than a minute from Peltier to sample, with no drift in temperature throughout measurement</li>
				<li>The crosstalk is not noticable as larger than usual measurement noise.</li>
                </ul>
                I designed the vacuum chamber, heatsink and control box and then wrote a custom python interface for the control box to hide a lot of the dangerous settings available in the proprietary software for the temperature controller supplier. A Peltier device was chosen as the temperature control mechanism because it can be used to both heat and cool the sample space. Click the link below to find out why this made the design so challenging and to learn more about the system's applications. A scientific paper describing the key features and operating parameters is a WIP.
                </p>
				<ul class="actions">
					<li><a href="/projects/#Room_Temperature_System" class="button next">More on the RTS</a></li>
					<li><a href="/projects/" class="button">See more projects</a></li>
				</ul>
			</div>
		</div>
	</section>
    <section>
        <span class="image">
            <img src="{% link /assets/img/tiles/crokinole.jpg %}" alt="" data-position="center center" />
            <p class="align-center">Crokinole Board, Discs and Bowl</p>
        </span>span>
        <div class="content">
            <div class="inner">
                <header class="major">
                    <h3>Woodwork and DIY</h3>
                </header>
                <p>I really like to make things (as if that wasn't already clear) and one of the easiest materials to get started with is wood because the materials are readily available and it is possible to do a lot of things with few expensive tools (by using hand tools). It is for this reason that most of my projects are woodworking, not because it is my favourite. To get where I am now, I learned most of what I know from my dad but also worked as a joiner's labourer during many of my undergraduate holidays. Recently I have been working on garden furniture: planters, <a href="\assets\img\projects\misc\compost bin 01 - finished product.jpg">compost bin</a> and a <a href="\assets\img\projects\misc\Bench 01.jpg">bench</a>. These were all made from recycled pallets wood during lockdown, which seems to have been a trend. This was done almost entirely without power tools, only using a hand me down orbital sander and drill + impact driver duo. When I head home to visit my parents, I try to do projects with them since my mum is overflowing with ideas and my dad is much more equipped and has the space and money for more sophisticated projects. In summer 2020 I <a href="\assets\img\projects\misc\tiling 02.jpg">tiled</a> their downstairs bathroom and did a few small DIY projects with my dad (including fitting <a href="\assets\img\projects\misc\dads lights 01.jpg">LED light strips</a> in the workshop) but over that Christmas break we made a <a href="/projects/#Crokinole_Board">crokinole board</a> (a tabletop game somewhere between curling/boules and pool with DNA from shuffleboard and air hockey) to play with family and friends. The following year we made a <a href="/projects/#Chess_Board">chess board</a>. In the past my dad and I made a <a href="/projects/#Futon_Bed_Project">folding bed</a>, a <a href="/projects/#Peripheral_Rack">headphone and xbox 360 controller stand</a> and several other small projects. It is always a joy to have access to his tools, knowledge and company!</p>
                <ul class="actions">
                    <li><a href="/projects/#Crokinole_Board" class="button next">More on Crokinole</a></li>
                    <li><a href="/projects/#Chess_Board" class="button next">More on the Chess Board</a></li>
                    <li><a href="/projects/" class="button">See More Projects</a></li>
                </ul>
            </div>
        </div>
    </section>
	<section>
        <span class="image">
            <img src="{% link /assets/img/projects/2WireLEDDriver/01 - Finished, lid off.jpg %}" alt="" data-position="center center" />
            <p class="align-center">Assembled dimmable 2-wire LED driver.</p>
        </span>
        <div class="content" id="electronics">
            <div class="inner">
                <header class="major">
                    <h3>Electronics</h3>
                </header>
                <p>I have undertaken many small electronics projects, such as replacing a power supply in an old BBC Master computer, making cables or analogue filters for laser experiments and the box for the temperature controller in the RT system. The two other largest projects are a cartridge emulator for Atari 8-bit series computers using, an Arduino Mega, with plans to replace it with a PIC after the proof of concept stage, and a display board demonstrating the function of an 8-bit adder for outreach purposes. I have also focused on hardware-software interfacing in programming for my research and in my contribution to hackathon entries (see <a class="scrolly" href="#programming">Programming</a> for more on hackathons) but I  helped with all the circuitry in those projects (where applicable). My most impressive electronics project is the following LED driver.</p>
                <p>Two-wire LED drivers work by oscillating the polarity of a driving DC current applied to a string of LEDs with sections of opposing polarity LEDs. This allows for easy assembly and control of the LEDs for animations and so on for Christmas lights. Typically, the controllers come programmed with several fun animations however they were all too bright for me and I just wanted soft lighting. I wanted to make a simple dimmable LED string driver for a 2-wire LED chain. As always, things got out of hand and the project ended up quite sophisticated. See the image on the right for a sneak-peak and click below to find out more.</p>
                <ul class="actions">
                    <li><a href="/projects/2WireLEDDriver/" class="button next">More on LED Driver</a></li>
                    <li><a href="/projects/" class="button">See more projects</a></li>
                </ul>
            </div>
        </div>
    </section>
    <section>
        <span class="image">
            <img src="{% link /assets/img/tiles/balding gate.png %}" alt="" data-position="center center" />
            <p class="align-center">Balding Gate level editor</p>
        </span>
        <div class="content" id="programming">
            <div class="inner">
                <header class="major">
                    <h3>Programming</h3>
                </header>
                <p>I've been writing code as a hobby since my first week at university, mostly for scientific purposes but also at <a href="https://en.wikipedia.org/wiki/Hackathon">hackathons</a> (24 hour programming/hardware competitions) and for fun. My teams and I are very proud to say that we won prizes at most of the hackathons we attended and typically stood out as the only hardware projects on display. Our projects include an Amazon Alexa controlled robot Budweiser box and a dice rolling app for the (now discontinued) pebble classic smart watch. During my PhD, I created an <a href="https://github.com/stupoole/Instruments">instrument control package</a> containing classes for each instrument used regularly and methods to control them in typical applications. The classes also provide a way to control the instruments in unique ways. For this package, I also wrote scripts which utilise the package as <a href="https://github.com/stupoole/instrumentsexamples">examples</a> and to be used/modified for standard experiments.</p>
                <p>Apart from the following application, my most significant programming projects are this website and the instruments package written for my research group which is an interface for controlling the equipment used by the group. The biggest programming endeavour, however, is a game called Balding Gate which I am working on whenever my brother and I are together.</p>
                <p>On one warm night in Shoreditch, London, my brother was explaining the power of Kotlin to me, and describing how easy to learn, yet powerful it is. In a later discussion we were talking about a game called Baldur's Gate (hence the project name) and came up with an idea for an application which can be used to design, and also play out, encounters for tabletop role playing games such as dungeons and dragons. We thought it would be a good opportunity to use Kotlin and decided on a brief. It would be really cool to have a way to interactively draw a map, set up player characters, allies and enemies on that map and to then give them customisable rules and behaviours which the person running the encounter would implement in the tabletop game. This could be used to handle all the nitty gritty rules which slow down play and to mitigate the "total party kill" scenario (in which all the players die and the game is over) by testing the encounter beforehand. With this in place, the application could be used for story telling and as an open source "game engine" for turn and tile based games. The project is at a preliminarily working stage, in which the user can make and play out a scenario, however most of the editing is done outside of the app and the behaviours are baked in at this stage. To see more about this project or to learn about projects in other programming languages, click the links below.</p>
                <ul class="actions">
                    <li><a href="/code/balding gate/" class="button next">More on Balding Gate</a></li>
                    <li><a href="https://github.com/stupoole" class="button"><icon class="fab fa-github"></icon> View on GitHub</a></li>
                    <li><a href="/code/" class="button">More programming projects</a></li>
                </ul>
            </div>
        </div>
    </section>
    <section>
        <a class="image">
            <img src="{% link /assets/img/tiles/me.png %}" alt="" data-position="center center" />
            <p class="align-center"></p>
        </a>
        <div class="content">
            <div class="inner">
                <header class="major">
                    <h3>What makes me tick</h3>
                </header>
                <p>I hope you found my projects interesting and have learned something from them! If you're wondering what kind of person I am, and how I find time for these alongside my studies and life, you'll be glad to hear that I have a healthy work-life balance, finding time to cook and eat world foods, play board games and video games, socialise with friends, listen to a lot (and I mean a lot) of different music, read books (sci-fi novels lately), hang out with my partner and go on adventures, hiking in the woods, climbing mountains and exploring new cities. I also watch a lot of educational material on youtube (more technical than most people's), especially people like This Old Tony, who invites us into his shop to learn alongside him, with some incredibly cheesy gags and "dad jokes" along the way. Another favourite is Wintergatan, with his never ending Marble Machine X project, in which he tries to combine an entire secondary school music room with a marble run to make beautiful music (I believe!). I regularly look to EEVBlog for electrical engineering advice and to learn about novel circuits and "traps for young players" such as myself. For machining advice, I look to Abom79 and his sage-like patience. I sometimes even watch CAD tutorials for fun... If I can't find what I want there, I look around for other sources of reliable information, talk to real people or post on forums. I find an answer to your problem is much less valuable than an explanation of the problem at hand and a teacher is the best way to get that.</p>
                <p>If you've read this far and are hiring, I'm really hoping you're now at the stage where you're thinking "these projects are interesting andthis guy seems capable, but is he a good fit for our company ethos?" First, thank you for considering me! I'd like to describe myself briefly, if I may. </p>
                <p>Although this site is fairly casual (for the sake of preserving some essence of personality!) I am professional and responsible. With all my projects, I am concerned with my safety, the safety of the users and the safety of those around me, taking all necessary precautions and wearing suitable PPE even (especially) when at home.  In terms of cultural values, I am very progressive and open-minded and love surrounding myself with people from diverse backgrounds and learning from them and improving myself all the time. I always aim to treat people fairly and include them whenever I can, making sure they feel trusted. I am environmentally conscious and avoid unnecessary travel, especially flights (also, I don't drive or have a motor vehicle), and am opposed to wastefulness and planed obsolescence; I would much rather take apart and repair something broken than buy new every time something breaks. I remain positive in the face of defeat and have a real passion for making things, both large and small, complex and simple. I hope that my projects display my passion for engineering and demonstrate my innovation and creativity. I believe, that with the right guidance, I can achieve anything.</p>
               <p> If you're wondering if I have any deal breaking personality traits, well I doubt it, but I do have a few peculiarities. For one, I have a tendency to find problems with things other people have no problem with. I customise everything I own to make it as nice as possible: I am a tinkerer. I tinker with everything. I oil hinges, I tighten screws, I change key bindings, I modify packages, I change colour schemes, I enable developer mode on my phone just to reduce the animation duration on overswipes, I 3D print a replacement part for a fan bracket, I make a doorstop to stop the door banging. It's not that I'm a perfectionist, I just don't let solvable problems persist. It is because of this trait that people know I fix things. Now I am asked to fix things by everyone who knows me. Computer not working? Take it to Stu. Bike broken? Stu. Espresso machine seized up with limescale? Stu. Fuse blown? Stu. Broken cable? Stu. Want to remove a fireplace? Stu (although I might need a hand with that one).</p>
               <p> For another, I like the dark, the winter and the cold. Most people love going to sunny places to enjoy the beach, but I prefer cold and snow. I dragged my partner to Sweden in the middle of January a few years back and, while she enjoyed the city, food and entertainment, my favourite part was definitely the weather. </p>
               <p>For a third, I don't care for statistics and trivia and find pub quizzes incredibly challenging because of this! I enjoy them, and did them regularly for a while, but my team and I were last in all rounds almost every time. Hopeless! The thing is, I could tell you something incredibly niche about some piece of 80s media format, but couldn't tell you the name of an England football player no matter how many times I've heard their names.</p>
            </div>
        </div>
    </section>
</section>
<section id="five">
	<div class="inner">
		<header class="major">
			<h2>Thank you for taking an interest!</h2>
		</header>
		<p>If you are wanting further information about any of these projects or are considering offering me a chance to apply to work at your company, please do not hesitate to contact me using the form below. If you would like more information about me, my life, and how I got here, see the link below.</p>
		<ul class="actions">
		    <li><a href="#contact" class="button scrolly">Contact me</a></li>
			<li><a href="/about/" class="button next">More about me</a></li>
		</ul>
		<ul class="actions">
            <li><a href="#banner" class="button special scrolly">Back to top</a></li>
		</ul>
	</div>
</section>

</div>
