---
title: Collaborazioni
layout: page
---
In questa sezione del nostro blog troverete le tante collaborazioni che abbiamo con circoli, eqipaggi, aziende e classi veliche. Se vuoi la tua licra personalizzata contattaci [qui](https://ig.me/m/caketussy) o scrivici una mail a [caketussy@gmail.com](mailto:caketussy@gmail.com)!

{% for post in site.categories.collabs %}
  <div style="display: flex; align-items: center; margin-bottom: 20px;">
    <img src="{% if post.thumbnail %}{{ post.thumbnail | prepend: site.baseurl }}{% else %}{{ site.baseurl }}/assets/images/default-thumb.png{% endif %}" alt="{{ post.title }}" style="width: 100px; height: auto; margin-right: 20px;">
    <div>
      <h2><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt }}</p>
    </div>
  </div>
{% endfor %}

