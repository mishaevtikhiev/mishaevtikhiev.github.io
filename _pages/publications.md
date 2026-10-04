---
layout: archive
title: "Publications"
description: "Publications by Mikhail Evtikhiev on machine learning for code, software engineering, and theoretical physics."
permalink: /publications/
author_profile: true
---

{% include base_path %}

<p style="margin-bottom: -10px; padding-bottom: 0; color: #888888"><i><b>J</b> — Journal papers. <b>C</b> — Conference papers. <b>W</b> — Workshop papers. <b>P</b> — Pre-prints and technical reports.</i></p>

<h2>Machine learning for code</h2>

{% assign ml_pubs = site.publications | where: "category", "ml4code" | sort: "date" | reverse %}
{% for post in ml_pubs %}{% if post.pinned %}
  {% include archive-single.html %}
{% endif %}{% endfor %}
{% for post in ml_pubs %}{% unless post.pinned %}
  {% include archive-single.html %}
{% endunless %}{% endfor %}

<h2>Software engineering</h2>

{% assign se_pubs = site.publications | where: "category", "se" | sort: "date" | reverse %}
{% for post in se_pubs %}
  {% include archive-single.html %}
{% endfor %}

<h2>Theoretical physics</h2>

{% for post in site.publicationsphysics reversed %}
  {% include archive-single.html %}
{% endfor %}
