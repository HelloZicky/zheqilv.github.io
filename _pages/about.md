---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}



{% include_relative includes/intro.md %}

{% include_relative includes/pub.md %}

{% include_relative includes/award.md %}

<!-- {% include_relative includes/edu.md %} -->

<!-- {% include_relative includes/work.md %} -->

<br />
<br />
<br />
<br />
<br />

[//]: # (<div style="text-align: center; line-height: 100px">)

[//]: # ()
[//]: # ([//]: # &#40;<a href='https://clustrmaps.com/site/1bq4k'  title='Visit tracker'><img src='//clustrmaps.com/map_v2.png?cl=ffffff&w=300&t=tt&d=USVT5ZdiMifi_f-uIMrY3tmJJC5s1RLU2rz5sVs8mjY'/></a>&#41;)
[//]: # (<a href="https://clustrmaps.com/site/1c4l8"  title="ClustrMaps"><img src="//www.clustrmaps.com/map_v2.png?d=wbCANDozCuOy1MbWWVWYbL3ny9ukUGAYXSFvZ_6GrIQ&cl=ffffff" /></a>)

[//]: # (</div>)

<script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=wbCANDozCuOy1MbWWVWYbL3ny9ukUGAYXSFvZ_6GrIQ&cl=ffffff&w=a"></script>
[//]: # (<!-- <script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=USVT5ZdiMifi_f-uIMrY3tmJJC5s1RLU2rz5sVs8mjY&cl=ffffff&w=a"></script> -->)
