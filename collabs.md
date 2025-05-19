---
title: Collaborazioni
layout: page
---
In questa sezione del nostro blog troverete alcune delle tante collaborazioni che abbiamo con circoli, eqipaggi, azienda e classi veliche. Se vuoi la tua licra personalizzata contattaci [qui](https://ig.me/m/caketussy)!

{% for post in site.categories.collabs %}
  <div style="display: flex; align-items: center; margin-bottom: 20px;">
    <img src="{% if post.thumbnail %}{{ post.thumbnail | prepend: site.baseurl }}{% else %}{{ site.baseurl }}/images/default-thumb.jpg{% endif %}" alt="{{ post.title }}" style="width: 100px; height: auto; margin-right: 20px;">
    <div>
      <h2><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt }}</p>
    </div>
  </div>
{% endfor %}
