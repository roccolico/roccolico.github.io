---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## The full list of my publications is available [here](https://ui.adsabs.harvard.edu/search/q=%20author%3A%22lico%2C%20rocco%22&sort=date%20desc%2C%20bibcode%20desc&p_=0){:target="\_blank"}.
---

## Some very recent publications:

{% for publi in site.data.publist %}

 <strong> {{ publi.title }} </strong> <br />
 <span style="color:grey"> <em>{{ publi.date }},  {{ publi.journal }} </em> </span> <br />
  <em>{{ publi.authors }} </em><br /> <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
 
{% endfor %}





