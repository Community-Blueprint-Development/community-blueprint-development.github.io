---
title: "Mental Health Workshop"
categories:
  - Post Formats
tags:
  - image
  - Post Formats
---

{% capture fig_img %}
[![CBDF Reading and Wellness Festival](/assets/images/mental-health.jpg)](https://communityblueprintdevelopment.org)
{% endcapture %}

{% capture fig_caption %}
CBDF Partnership Event: Mental Health Workshop
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>{{ fig_caption | markdownify | remove: "<p>" | remove: "</p>" }}</figcaption>
</figure>

Need more information or have questions?

[Contact Us]({{ "/pages/contact/" | relative_url }}){: .btn .btn--success .btn--large}




