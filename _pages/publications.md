---
title: "HUMANE Lab - Publications"
layout: gridlay
excerpt: "HUMANE Lab -- Publications."
sitemap: false
permalink: /publications/
---


# Publications

(You can also refer to [Google Scholar](https://scholar.google.com/citations?user=xiZ1ImoAAAAJ&hl=en))

*\*: Equal contribution*

{% for publi in site.data.publist %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}
