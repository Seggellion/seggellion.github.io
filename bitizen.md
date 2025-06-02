---
title: Star Bitizen Trade API
layout: landing
description: 'A Twitch-connected trading game API set in the Star Citizen universe. Players buy, sell, and transport commodities across planets and space stations using a Rails-powered tick-based economy.'
image: assets/images/pic03.png
nav-menu: true
---

<!-- Main -->
<div id="main">

<!-- One -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h2>A Rails API for Galactic Trade on Twitch</h2>
		</header>
		<p>
Star Trader is a custom Ruby on Rails 8 API built for a real-time, chat-driven trading game integrated with Twitch. Players explore the Star Citizen universe by buying, selling, and hauling commodities between locations like planets, moons, and stations—all within a dynamic, tick-based economy.
		</p>
	</div>
</section>

<!-- Two -->
<section id="two" class="spotlights">
	<section>
		<a href="#" class="image">
			<img src="{% link assets/images/starbitizen1.png %}" alt="" data-position="center center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Game Mechanics Driven by Real Economics</h3>
				</header>
				<p>
				Players use cargo ships to transport SCU-limited goods, earning credits through smart trade decisions. Supply and demand fluctuate over time, influenced by facility stock and city consumption. Every action—buy, sell, travel—impacts the shared economy across the entire server.
				</p>
				<ul class="actions">
					<li><a href="#" class="button">View Data</a></li>
				</ul>
			</div>
		</div>
	</section>
	<section>
		<a href="#" class="image">
			<img src="{% link assets/images/starbitizen3.png %}" alt="" data-position="top center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Twitch Integration and Player Identity</h3>
				</header>
				<p>
				Each player is identified by their Twitch username. The API listens to chat commands and responds in real-time, creating a persistent economy tied to live audience interaction. Star Trader is built for streamers who want to offer gameplay directly from their channel.
				</p>

			</div>
		</div>
	</section>
	<section>
		<a href="#" class="image">
			<img src="{% link assets/images/starbitizen2.png %}" alt="" data-position="25% 25%" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Built with Rails 8 and Modular Systems</h3>
				</header>
				<p>
				The system includes models for ships, locations, cargo, and travel. Features like jumpgates, tick scheduling, price inflation, and capacity management are modular and extensible. The backend is designed for performance and scalability across thousands of transactions.
				</p>
				<ul class="actions">
					<li><a href="https://starbitizen.com" class="button">Learn more</a></li>
				</ul>
			</div>
		</div>
	</section>
</section>

<!-- Three -->
<section id="three">
	<div class="inner">
		<header class="major">
			<h2>An Extensible Foundation for Future Gameplay</h2>
		</header>
		<p>Star Trader is not just a game—it's a framework for persistent, player-driven economies in sci-fi universes. Future updates may include mining, piracy, or faction control. The API can be expanded to other platforms or integrated with modded Minecraft or real-time web dashboards.</p>
		<ul class="actions">
			<li><a href="https://starbitizen.com" class="button next">Get Started</a></li>
			<li><a href="https://github.com/Seggellion/startrader" class="button next">GitHub</a></li>
		</ul>
	</div>
</section>

</div>
