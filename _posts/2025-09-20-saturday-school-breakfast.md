---
title: "Saturday School Breakfast"
permalink: /_posts/2025-09-20-saturday-school-breakfast
categories:
  - Post Formats
tags:
  - image
  - Post Formats
---

{% capture fig_img %}
<a href="https://communityblueprintdevelopment.org">
  <img src="../assets/images/Sat-School-Breakfast-Artifact.png" alt="Saturday School Partnership Breakfast" style="width:100%;max-width:800px;display:block;margin:0 auto;" />
</a>
{% endcapture %}

{% capture fig_caption %}
<!-- Add caption text here if needed -->
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>{{ fig_caption | markdownify | remove: "<p>" | remove: "</p>" }}</figcaption>
</figure>

Need more information or have questions?

[Contact Us]({{ "/contact/" | relative_url }}){: .btn .btn--success .btn--large}
*— Community Blueprint Development — "Just for YOUth!"*





