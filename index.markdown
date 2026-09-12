---
layout: default
title: Binary Solo
---

<section class="hero">
	<div class="background-image" style="background-image: url('assets/images/hisato-hero.webp')"></div>
	<div class="wrapper">
		<div class="copy container">
			<h1>Hisato no Saku</h1>
			<p>Available now on <a href="https://store.steampowered.com/app/1508370/Hisato_no_Saku/">Steam</a>, <a href="https://binarysolo.itch.io/hisato-no-saku">itch.io</a>.</p>
		</div>
	</div>
</section>

<section class="page-section about" id="about">
	<div class="container">
		<h1 class="left">Porting</h1>
		<h1 class="center">Co-development</h1>
		<div class="right">
			<h1 style="display: inline-block">Originals</h1>
		</div>
		<p class="center" style="margin-top: 4rem;">Whether we're optimizing, bringing games to mobile, or dreaming up something new; We strive
		to bring quality.</p>
	</div>
</section>

<section class="page-section portfolio" id="portfolio">
    <div class="container">
        <!-- Portfolio Section Heading-->
        <div class="section-heading-background">
            <h1 class="page-section-heading text-secondary mb-0 d-inline-block">Our Games</h1>
        </div>
        <!-- Portfolio Grid Items-->
        <div class="games row justify-content-center">
            <!-- Portfolio Items-->
			{% for game in site.data.games %}
				{% include game.html game=game %}
			{% endfor %}
        </div>
    </div>
</section>
