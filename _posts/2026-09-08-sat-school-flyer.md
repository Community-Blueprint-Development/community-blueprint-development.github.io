---
title: "Saturday School Fall 2026"
permalink: /_posts/2026-09-08-sat-school-flyer
categories:
  - Post Formats
tags:
  - image
  - Post Formats
---

{% capture fig_img %}
[![InspiredU Flyer](../assets/images/Saturday-School-Flyer.png)](https://communityblueprintdevelopment.org)
{% endcapture %}

{% capture fig_caption %}

{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>{{ fig_caption | markdownify | remove: "<p>" | remove: "</p>" }}</figcaption>
</figure>

Need more information or have questions?

[Contact Us]({{ "/contact/" | relative_url }}){: .btn .btn--success .btn--large}
*— Community Blueprint Development — "Just for YOUth!"*
