---
layout: page
title: Tank Lab @ UIdaho Molecular Plant Systematics & Evolution
excerpt: "Plant Molecular Systematics & Evolution at the University of Idaho"
modified: 2015-06-06T02:41:00
image:
  feature: Castilleja-pumila.jpg
  credit: D. Tank
---

Research in the Tank Lab focuses on the use of molecular methods to reconstruct evolutionary  histories in plants and the application of phylogenetic and phylogeographic methods to understand plant evolution. 

Research in the lab focuses on multiple levels of plant phylogeny from the systematics and evolution of closely related groups of species to macroevolutionary patterns of diversification in angiosperms.   

Check out the [**research page**]({{ site.url }}/research.html) to learn more about how we use phylogenies to address evolutionary questions in plants and to better understand plant biodiversity.

## Recent lab news:

<ul class="post-list">
{% for post in site.posts limit:10 %} 
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span>{% if post.excerpt %} <span class="excerpt">{{ post.excerpt }}</span>{% endif %}</a></article></li>
{% endfor %}
</ul>

* Responsive templates. Looking good on mobile, tablet, and desktop.
* Gracefully degrading in older browsers. Compatible with Internet Explorer 9+ and all modern browsers.
* Minimal embellishments and subtle animations.
* Optional large feature images for posts and pages.
* [Custom 404 page]({{ site.url }}/404.html) to get you started.
* [Simple site search](https://github.com/christian-fei/Simple-Jekyll-Search)
* Support for Disqus Comments

<a markdown="0" href="{{ site.url }}/theme-setup" class="btn">Install So Simple Theme</a>

[^1]: Example: *domain.com/category-name/post-title*