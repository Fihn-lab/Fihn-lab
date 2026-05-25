---
title: Projects
nav:
  order: 2
  tooltip: Software, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

<p align="center">
  <img src="/Fihn-lab/images/quorumsensing.jpg" width="700">
</p>

Here you will find what were currently working on in the lab!

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}
