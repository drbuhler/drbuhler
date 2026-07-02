---
layout: page
title: Welcome
permalink: 
---


## [National Orthodox United Schools (NOUS)]()

NOUS is an open-source directory and library of resources for homeschoolers, co-ops, church schools, and private Orthodox schools. We offer conferences, resources, and select consulting services. 

- [“Teacher as Mentor,” *Into the Light*, St. Vladimir’s Press, 2025.]()
- School in a box (open source resources)

## Capital placement

*Numinor*, Tolkien’s name for the true west, is acquiring and rehabilitating unique and beautiful properties across the U.S. [Numinor Homes](https://www.498orca.com/) places capital into high velocity real assets and restoration projects for short term gains and long-term tax advantage. We take pride in restoring traditional spaces and providing homes for first time buyers. 

- [498orca.com](https://www.498orca.com/)
- Numinorhomes.com (coming soon)

## Latest Posts

{% for post in site.posts limit:2 %}
  <h3><a href="{{ post.url | absolute_url }}">{{ post.title }}</a></h3>
  <p class="date">{{ post.date | date: "%B %d, %Y" }}</p>
  <div class="entry">
    {{ post.excerpt }}
  </div>
{% endfor %}

## Ways to connect

* [Facebook](https://www.facebook.com/keithedbuhler)
* [Instagram](https://www.instagram.com/dionysiusbuhler/)
* [YouTube](https://www.youtube.com/c/KeithBuhler)
* [Blog](https://buhler.notion.site/Buhler-Report-Blog-Current-9d90055115754d97b5c7f15d09005eae)
* [Questions for Reflection](http://keithbuhler.com/pensees)
