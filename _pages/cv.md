---
layout: archive
title: "CV"
description: "CV of Mikhail Evtikhiev: Senior ML Researcher at JetBrains Research working on post-training and evaluation of code LLMs."
permalink: /cv/
author_profile: true
---

{% include base_path %}

<!-- Publications are pulled from the _publications/_publicationsphysics collections. Keep the rest in sync with LinkedIn. -->
<!-- TODO(misha): link a PDF version once the CV build pipeline is agreed. -->

## Experience

**Senior ML Researcher**, [JetBrains Research](https://www.jetbrains.com/research/) — Jan 2026 – present
- Leads applied research projects with teams of 2–3 researchers.
- Mentors research interns on training-data filtering and synthesis.
- Post-training and transfer: when gains from SFT/RL on one task family transfer to others; LoRA vs. full fine-tuning; multi-task and continual learning.
- Evaluation methodology: construct validity of coding benchmarks, task taxonomies, auditing evaluation harnesses for spurious passes and failures.

**ML Researcher**, [JetBrains Research](https://www.jetbrains.com/research/) — Sep 2020 – Dec 2025
<!-- TODO(misha): describe public 2024–2025 work in this role (beyond Kotlin ML Pack) at the level of method and question. -->
- Machine learning for code: evaluation of code-generation models, optimizers for ML-for-code tasks, Kotlin ML Pack.
- 2020–2023: collaboration-tools research (bus factor, code review, mining socio-technical data) using mixed methods.

**Eastern Europe Outreach Coordinator** (part-time), [Weizmann Institute of Science](https://weizmann.ac.il) — 2016 – 2020
- Within three years, MSc applications from Eastern Europe doubled and the number of admitted students increased fivefold.

**Teaching Assistant**, [Weizmann Institute of Science](https://weizmann.ac.il) — 2014 – 2020
- Quantum Field Theory I (2015–2020); Quantum Mechanics II (2014–2015).

## Education

**PhD, Theoretical Physics**, Weizmann Institute of Science — 2015 – 2020
- Thesis: "On Superconformal Field Theories and Little String Theories". Advisor: Prof. Ofer Aharony.

**MSc, Theoretical Physics**, Weizmann Institute of Science — 2013 – 2015
- Thesis: "On four dimensional N = 3 superconformal theories". Advisor: Prof. Ofer Aharony.

**BSc with honors in Physics (Astrophysics)**, St Petersburg Polytechnical University — 2009 – 2013
- Thesis: "On properties of Lane-Emden equation". Advisor: Prof. Dmitry Varshalovich.

## Publications

### Machine learning for code
<ul>
{% assign ml_pubs = site.publications | where: "category", "ml4code" | sort: "date" | reverse %}
{% for post in ml_pubs %}{% include cv-publication.html %}{% endfor %}
</ul>

### Software engineering
<ul>
{% assign se_pubs = site.publications | where: "category", "se" | sort: "date" | reverse %}
{% for post in se_pubs %}{% include cv-publication.html %}{% endfor %}
</ul>

### Theoretical physics
<ul>
{% for post in site.publicationsphysics reversed %}{% include cv-publication.html %}{% endfor %}
</ul>

## Advising

<!-- TODO(misha): JetBrains research intern mentoring (see /service/). -->
- 2022–2023: Co-advisor, Vahid Haratian (Bilkent University).
- 2021–2022: Advisor, Dmitry Pasechnyuk and Anton Prazdnichnykh (HSE University).
- 2021: Co-advisor, Elgun Jabrayilzade (Bilkent University).

## Reviewing

- 2024: SANER, Research Track sub-reviewer.
- 2023: MSR, Technical Track Junior PC.
- 2023: Bachelor thesis review, Constructor University.

## Honors

- Second prize, International Mathematical Competition (2013).
- Winner, Russian Student Physics Olympiad, team event (2011).
