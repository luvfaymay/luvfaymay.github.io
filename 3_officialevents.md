---
title: Official Events
layout: landing
description: ""
image: assets/images/swsh22.jpeg
nav-menu: true
---

<!-- Main -->
<div id="main">
    <section id="one">
        <div class="inner">
            <header class="major">
                <h2>{{ site.translations[site.lang].official_events.title }}</h2>
            </header>
            <p>{{ site.translations[site.lang].official_events.translation_status }}</p>
            <p>{{ site.translations[site.lang].official_events.description }}</p>
        </div>
    </section>
    <section id="two" class="spotlights">
        <section>
            <div class="image">
				<img src="{{ 'assets/images/idfgd.jpeg' | relative_url }}" alt="idfgd" data-position="center center">
			</div>
            <div class="content">
                <div class="inner">
                    <header class="major">
                        <h3>{{ site.translations[site.lang].official_events.event1.title }}</h3>
                    </header>
                    <p>{% t official_events.event1.description %} <a class="vote-link" href="https://idf-girlsday.ponycanyon.co.jp/">{% t official_events.event1.event1_link %}</a></p>
                </div>
            </div>
        </section>
    </section>
</div>
