---
title: "Small Business Training"
permalink: /_posts/2026-09-08-business-training
categories:
  - Post Formats
tags:
  - image
  - Post Formats
---

{% capture fig_img %}
[![InspiredU Flyer](../assets/images/business-flyer-092026.png)](https://communityblueprintdevelopment.org)
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
