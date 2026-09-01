---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<p>For a complete, real-time citation record and metrics, visit my <strong><a href="https://scholar.google.com/citations?user=Gacl34sAAAAJ" target="_blank" rel="noopener noreferrer">Google Scholar Profile</a></strong> or <strong><a href="https://www-robotics.jpl.nasa.gov/people/joseph_bowkett/" target="_blank" rel="noopener noreferrer">JPL Robotics Profile</a></strong>.</p>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

