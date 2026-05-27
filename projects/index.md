---
title: Projects
nav:
  order: 1
  tooltip: Find our current projects here!
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

<p align="center">
  <img src="/Fihn-lab/images/quorumsensing.jpg"
       style="display:block; margin:0 auto; width:90%; max-width:1000px;">
</p>

Quorum sensing is a form of bacterial communication in which microbes produce and detect small signaling molecules to coordinate group behaviors. At low cell density, signaling molecules are produced but remain too dilute to strongly activate quorum sensing pathways. As the bacterial population grows, these molecules accumulate and eventually reach concentrations high enough to trigger coordinated changes in gene expression across the community. In the opportunistic pathogen *Pseudomonas aeruginosa*, quorum sensing controls processes such as biofilm formation and virulence factor production. Research in the lab focuses on understanding and manipulating these signaling pathways through biosynthesis, chemical biology, and mass spectrometry to better understand microbial communication and identify new antivirulence strategies.

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}
