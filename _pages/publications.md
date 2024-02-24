---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

1. ‘Mapping Indian Land Laws: A review of right Indian states’, CPR, 2022 →
2. ‘Tracking Reforms in Land Leasing and Change in Land Use: Insights from Gujarat and Karnataka’,
Carnegie India, 2021 →
3. ‘The Legal Regime and Political Economy of Land Rights in the Scheduled Areas of India’, CPR, 2018 →
4. ‘Land Acquisition in India: A review of Supreme Court cases from 1950 to 2016’, CPR, 2017 →
5. ‘Building Smart Cities in India: Allahabad, Ajmer, and Visakhapatnam’, Brookings India, 2016 →

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
