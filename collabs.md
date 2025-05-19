---
title: Collaborazioni
layout: page
---
In questa sezione del nostro blog troverete alcune delle tante collaborazioni che abbiamo con circoli, eqipaggi, azienda e classi veliche. Se vuoi la tua licra personalizzata contattaci [qui](https://ig.me/m/caketussy)!

{% for post in site.categories.collabs %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}
