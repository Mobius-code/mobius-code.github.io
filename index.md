---
layout: main
title: Mobius Code
---
<div id="title">
    <a href="/"><img id="logo" src="/assets/logo.png" alt="Chimera Linux logo"></a>
    <span>
        This is a website about coding
    </span>
    <nav class="buttons">
        <a id="button_download" href="/downloads">Downloads</a>
        <a id="button_packages" href="{{ site.pkgs_link }}">Packages</a>
    </nav>
    <nav class="social">
        {% for soc in site.social_links %}
            <a href="{{ soc[2] }}"><img src="/assets/icons/{{ soc[0] }}.svg" alt="{{ soc[1] }}"></a>
        {% endfor %}
    </nav>
</div>

<main id="desc">
    <p>
        Some code samples
    </p>
    <p>
        More code samples
    </p>
    <p>
        <a href="/about">Read more</a> for details.
    <p>
</main>

<div id="tile1" class="tile">
    <h1>GNU C Compiler.</h1>
    <p>
        Something about compilers.
    </p>
    <div class="more">
        <a href="/about#yesandno">Read more</a>
    </div>
</div>

<div id="tile2" class="tile">
    <h1>Another Heading.</h1>
    <p>
        Some more ridiculous text
    </p>
    <div class="more">
        <a href="/about#yes">Read more</a>
    </div>
</div>

<div id="tile3" class="tile">
    <h1>And yet another header.</h1>
    <p>
        Some more text.
    </p>
    <div class="more">
        <a href="/about#buildable-from-source">Read more</a>
    </div>
</div>

<div id="tile4" class="tile">
    <h1>Last One.</h1>
    <p>
        Last paragraph 
    </p>
    <div class="more">
        <a href="/about#portable">Read more</a>
    </div>
</div>

<div id="bottom">
    <h2><a href="/news">Recent news</a></h2>
    {% for post in site.posts limit:2 %}
    <div class="bottom_post">
        <h4>{{ post.date | date: "%B %d, %Y" }}</h4>
        <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
        {{ post.excerpt }}
        <p><a href="{{ post.url }}">Read more</a></p>
    </div>
    {% endfor %}
</div>
