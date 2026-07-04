---
layout: page
title: Welcome
permalink: 
---


## NOUS - [National Orthodox United Schools](https://drbuhler.github.io/schools/)

NOUS is an organization dedicated to supporting Orthodox education worldwide. We offer an open-source directory, a resource library, and select consulting services  for homeschoolers, co-ops, church schools, and private Orthodox schools. Consider attending our [2026 Educator's conference](https://www.stnektarioseducators.com/). 

- [Join the directory](emailto:dionysiusbuhler@gmail.com)
- [School in a Box](https://buhler.notion.site/St-Andrew-School-in-a-Box-f4868e0ee5b542c9b41b45ae803cea33) (open source resource library)
- (Consulting services)(/testimonials

## Numinor - Capital placement 

*Numinor* is an investment firm focused on rehabilitating unique and beautiful properties across the U.S.

[Numinor Homes](https://www.498orca.com/) places capital into high velocity real assets and restoration projects for short term gains and long-term tax advantage. We take pride in restoring traditional spaces. 

- A sample restoration project in Morro Bay: [498orca.com](https://www.498orca.com/)
- [Numinorhomes.com](

---

## The Latest

{% for post in site.posts limit:2 %}
  <h3><a href="{{ post.url | absolute_url }}">{{ post.title }}</a></h3>
  <p class="date">{{ post.date | date: "%B %d, %Y" }}</p>
  <div class="entry">
    {{ post.excerpt }}
  </div>
{% endfor %}
