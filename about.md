---
layout: default
title: About
---
## About {{ site.name }}

<img class="user-avatar" src="{{ site.owner.avatar }}">

I am an entrepreneur, educator, and philosopher based in Riverside, CA. 

My work spans classical education, restoring homes, and advisory services for Orthodox schools seeking to launch or be renewed. This page serves as a directory to my current projects and writing. (A complete record of academic publications, speaking engagements, and professional history at my CV)

After five years service as founding headmaster of St Andrew Academy, I now offer limited number of advisory services each year. I work primarily with educational boards on strategy, fundraising, and governance. I also encourage headmasters in creating positive teacher culture.  Inquire below.

<div class="pagination">
  {% if site.owner.linkedin %}
    <a href="{{ site.owner.linkedin }}" class="social-media-icons"><i class="fa fa-2x fa-linkedin-square" aria-hidden="true"></i></a>
  {% endif %}
  {% if site.owner.email %}
    <a href="mailto:{{ site.owner.email }}" class="social-media-icons"><i class="fa fa-2x fa-envelope-square" aria-hidden="true"></i></a>
  {% endif %}
  {% if site.owner.twitter %}
    <a href="https://twitter.com/{{ site.owner.twitter }}" class="social-media-icons"><i class="fa-brands fa-2x fa-square-x-twitter" aria-hidden="true"></i></a>
  {% endif %}
  {% if site.owner.github %}
    <a href="{{ site.owner.github }}" class="social-media-icons"><i class="fa-brands fa-2x fa-square-github" aria-hidden="true"></i></a>
  {% endif %}
</div>
