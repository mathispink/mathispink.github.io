---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: false
---

<p class="page-intro">Peer-reviewed papers and preprints, with brief summaries of the main contribution.</p>

{% assign pubs = site.publications | sort: "date" | reverse %}
{% for post in pubs %}
  {% include publication-card.html post=post %}
{% endfor %}
