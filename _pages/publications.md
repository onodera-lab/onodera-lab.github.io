---
title: "Onodera Lab - Publications"
layout: gridlay
excerpt: "Onodera Lab -- Publications."
sitemap: false
permalink: /publications/
---


# Publications

The most up to date list of publications is available on [Google Scholar](https://scholar.google.com/citations?user=RzvRJL8AAAAJ&hl=en). 

---

## Highlighted Publications

Please note that * denotes equal contribution.

{% for publi in site.data.highlight_publist %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}

---

## Other Publications

{% for publi in site.data.other_publist %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}
