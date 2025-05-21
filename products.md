---
title: Prodotti
layout: page
---
In questa sezione del nostro blog troverete tutte le licre della nostra linea originale. Per sapere come averle, contattateci [qui](https://ig.me/m/caketussy)!!

{% for post in site.categories.products %}
  <div style="display: flex; align-items: center; margin-bottom: 20px;">
    <img src="{% if post.thumbnail %}{{ post.thumbnail | prepend: site.baseurl }}{% else %}{{ site.baseurl }}/assets/images/default-thumb.png{% endif %}" alt="{{ post.title }}" style="width: 100px; height: auto; margin-right: 20px;">
    <div>
      <h2><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt }}</p>
    </div>
  </div>
{% endfor %}


