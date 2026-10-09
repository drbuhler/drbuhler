---
layout: default
title: "Pensées"
permalink: /pensees/
description: "Pensées: essays and reflections by Dionysius Buhler on philosophy, wisdom, attention, and the good life."
---
<!-- Posts appear here when their front matter includes the tag `pensees`, newest first. -->

## Pensées

{% assign pensees = site.posts | where_exp: "post", "post.tags contains 'pensees'" %}
{% for post in pensees %}
  <h3><a href="{{ post.url | absolute_url }}">{{ post.title }}</a></h3>
  <p class="date">{{ post.date | date: "%B %d, %Y" }}</p>
  <div class="entry">
    {{ post.excerpt }}
  </div>
{% endfor %}
