---
layout: page
title: Tank Lab @ UIdaho
excerpt: "Plant Molecular Systematics & Evolution at the University of Idaho"
modified: 2015-06-06T02:41:00
image:
  feature: Castilleja-pumila.jpg
  credit: D. Tank
---
# Molecular Plant Systematics & Evolution

The Tank Lab is in the [*Department of Biological Sciences*](http://www.uidaho.edu/sci/biology) at the [*University of Idaho*](http://www.uidaho.edu), and is affiliated with the [*Institute for Bioinformatics and Evolutionary Studies (IBEST)*](http://www.ibest.uidaho.edu) and the [*Stillinger Herbarium*](http://www.uidaho.edu/herbarium).

Research in the Tank Lab focuses on the use of molecular methods to reconstruct evolutionary  histories in plants and the application of phylogenetic and phylogeographic methods to understand plant evolution. 

Our work focuses on multiple levels of plant phylogeny, from the systematics and evolution of closely related groups of species to macroevolutionary patterns of diversification in angiosperms.   

Check out the [**research page**]({{ site.url }}/research.html) to learn more about how we use phylogenies to address evolutionary questions in plants and to better understand plant biodiversity.

## Recent lab news:

<ul class="post-list">
{% for post in site.posts limit:10 %} 
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span>{% if post.excerpt %} <span class="excerpt">{{ post.excerpt }}</span>{% endif %}</a></article></li>
{% endfor %}
</ul>

## Links

| -uidaho.edu- | -projects- | -societies- |
|:--------|:-------:|:--------|
| [Biological Sciences](http://www.uidaho.edu/sci/biology)   | [Consortium of PNW Herbaria](http://pnwherbaria.org/)   | [SSB](http://systbiol.org/)   |
| [Stillinger Herbarium](http://www.uidaho.edu/herbarium)   | [BEACON](http://beacon-center.org/)   | [BSA](http://www.botany.org/)   |
|----
| [IBEST](http://www.ibest.uidaho.edu)   | [iPlant Collaborative](http://www.iplantcollaborative.org)   | [ASPT](http://www.aspt.net/)   |
| [BCB](http://www.uidaho.edu/cogs/bcb)   | [My-Plant](https://my-plant.org)   | [ISPN](http://phylonames.org/)   |
|=====
| Foot1   | Foot2   | Foot3   |
{: .table}

[^1]: Example: *domain.com/category-name/post-title*