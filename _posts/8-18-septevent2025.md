
---
title: "Saturday School Partnership Breakfast"
categories:
  - Post Formats
tags:
  - image
  - Post Formats
---

{% capture fig_img %}
[![Saturday School Partnership Breakfast](assets/images/Saturday-School-Breakfast-Flyer-Final.jpg)](https://communityblueprintdevelopment.org)
{% endcapture %}

{% capture fig_caption %}
CBDF Partnership Event: Saturday School Parrnership Breakfast
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>{{ fig_caption | markdownify | remove: "<p>" | remove: "</p>" }}</figcaption>
</figure>

Need more information or have questions?

[Contact Us]({{ "/contact/" | relative_url }}){: .btn .btn--success .btn--large}



