---
permalink: /exhibitions/
title: "Exhibitions"
collection: exhibitions
---

[Instead of a list show here only pictures for the individual exhibitions,
most recent at the top, maybe when you hover over with the mouse you can see 
the name of the exhibition]

<ul>
{% for item in site.exhibitions %}
  <li>
      {{ item.year }}:<a href="{{ site.baseurl }}{{ item.url }}">{{ item.title }}</a>
  </li>
{% endfor %}
</ul>

