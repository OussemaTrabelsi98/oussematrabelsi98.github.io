---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

A list of all the posts and pages found on the site.

<h2>Pages</h2>
{% for post in site.pages %}
  {% unless post.url contains "/portfolio/" or post.url contains "/blog/" or post.url contains "/posts/" %}
    {% include archive-single.html %}
  {% endunless %}
{% endfor %}

{# Hide blog posts section entirely #}
{% assign written_label = 'None' %}

{% for collection in site.collections %}
  {% unless collection.output == false or collection.label == "posts" or collection.label == "portfolio" %}
    {% assign label = collection.label %}
    {% if label != written_label %}
      <h2>{{ label }}</h2>
      {% assign written_label = label %}
    {% endif %}
    {% for post in collection.docs %}
      {% include archive-single.html %}
    {% endfor %}
  {% endunless %}
{% endfor %}
