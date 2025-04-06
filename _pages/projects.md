---
permalink: /
title: Projects
collection: projects
---

I am an artist and scientist hailing from Scotland but based in Innsbruck. My artistic work explores the  boundaries of scientific and artistic inquiry/understanding and how they can generate meaning  in society -  I’m always revelling in the personal process, but never yet happy with the product.  My scientific research on glaciers focuses on connecting innovative field  measurements with mathematical modelling of systems. I have a BSc in Geography, a PhD in Glaciology and an MA in  Applied Art, and am a member of ParreTerre_6 studio in Innsbruck.

Here a list of my projects:

{% for item in site.projects %}
  <li>
      <a href="{{ site.baseurl }}{{ item.url }}">{{ item.title }}</a>
  </li>
{% endfor %}

