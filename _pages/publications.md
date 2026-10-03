---
layout: archive
title: "Publications"
description: "Publications by Mikhail Evtikhiev on machine learning for code, software engineering, and theoretical physics."
permalink: /publications/
author_profile: true
---

{% include base_path %}

<p style="margin-bottom: -10px; padding-bottom: 0; color: #888888"><i><b>J</b> — Journal papers. <b>C</b> — Conference papers. <b>P</b> — Pre-prints.</i></p>

<h2 >Software Engineering</h2>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<!-- <h2 >Collective Software Development</h2> -->

<!-- {% for post in site.ictl reversed %} -->
<!--   {% include archive-single.html %} -->
<!--   <b> works </b> -->
<!-- {% endfor %} -->


<h2 >Theoretical Physics</h2>

{% for post in site.publicationsphysics reversed %}
  {% include archive-single.html %}
{% endfor %}