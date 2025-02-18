---
title: Ongoing Votings
layout: landing
description: ""
image: assets/images/banner5.jpeg
nav-menu: true
---

<!-- Main -->
<div id="main">
    <section id="one">
        <div class="inner">
            <header class="major">
                <h2>{% t voting.title %}</h2>
            </header>
            <p>{% t voting.translation_status %}</p>
            <p>{% t voting.description %}</p>
            <ol>
                {% for instruction in site.translations[site.lang].voting.instructions %}
                    <li>{{ instruction }}</li>
                {% endfor %}
            </ol>
        </div>
    </section>
    <section id="two" class="spotlights">
        <section>
            <div class="image">
                <img src="{{ 'assets/images/thaiupdate.jpg' | relative_url }}" alt="thaiupdate" data-position="center center">
            </div>
            <div class="content">
                <div class="inner">
                    <header class="major">
                        <h3>{% t voting.thaiupdate.title %}</h3>
                    </header>
                    <p>{% t voting.thaiupdate.description %} <a class="vote-link" href="https://www.thaiupdate.info/couple-bromance-award-final/">{% t voting.thaiupdate.vote_link %}</a></p>
                </div>
            </div>
        </section>
        <section>
            <div class="image">
                <img src="{{ 'assets/images/vday.jpeg' | relative_url }}" alt="thaiupdate" data-position="center center">
            </div>
            <div class="content">
                <div class="inner">
                    <header class="major">
                        <h3>{% t voting.acervogl.title %}</h3>
                    </header>
                    <p>{% t voting.acervogl.description %} <a class="vote-link" href="https://x.com/glacervo/status/1891631265964556349">{% t voting.acervogl.vote_link %}</a></p>
                </div>
            </div>
        </section>
    </section>
</div>