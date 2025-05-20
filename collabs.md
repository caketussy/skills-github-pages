---
title: Collaborazioni
layout: page
---
In questa sezione del nostro blog troverete alcune delle tante collaborazioni che abbiamo con circoli, eqipaggi, azienda e classi veliche. Se vuoi la tua licra personalizzata contattaci [qui](https://ig.me/m/caketussy)!

{% for post in site.categories.collabs %}
  <div class="post-preview">
    <img src="{% if post.thumbnail %}{{ post.thumbnail | prepend: site.baseurl }}{% else %}{{ site.baseurl }}/assets/images/default-thumb.jpg{% endif %}" alt="{{ post.title }}">
    <div>
      <h2><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt }}</p>
    </div>
  </div>
{% endfor %}


