---
layout: single
permalink: /
author_profile: true
---

I am a third-year undergraduate student at The University of Texas at Arlington, where I am pursuing a Bachelor of Science in Computer Science. I am a web developer for the CSE department.

My research is in the emerging field of animal language processing, where I work on creating novel datasets and building machine learning models for analyzing canine vocal communication.

Please feel free to browse through my publications and news updates to get a better understanding of my work.

## News

{% for post in site.posts limit:5 %}
  {% include archive-single.html %}
{% endfor %}