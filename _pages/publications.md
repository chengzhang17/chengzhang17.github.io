---
#layout: archive
title: "Publications"
permalink: /publications/
#author_profile: true
---
Journal
======
[ToN21] Shaoran Li, Yan Huang, Chengzhang Li, Brian A Jalaian, Y Thomas Hou, Wenjing Lou,
and Stephen Russell, _“Maximize Spectrum Efficiency in Underlay Coexistence With Channel
Uncertainty,"_ IEEE/ACM Transactions on Networking, 2021.

Conference
======
22


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
