---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<p><a href="{{ base_path }}/files/Yongyi_Wang_CV_2026.pdf" class="btn btn--primary">Download current CV PDF</a></p>

Education
======
* Ph.D. student in Computer Science, Washington University in St. Louis, 2025-present

Research Interests
======
* Trustworthy AI-enabled cyber-physical systems
* Physical-world adversarial robustness
* Secure agentic AI systems
* Internet of Agents
* Robotics and perception security

Research Projects
======
{% assign research_items = site.portfolio | sort: "order" %}
<ul>{% for post in research_items %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

Publications
======
No accepted publications yet.

Teaching
======
<ul>{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

Advising
======
* Advisor: Prof. Ning Zhang
* Lab: <a href="https://cybersecurity.seas.wustl.edu/">CSPL Lab</a>
* School: Washington University in St. Louis

Contact
======
* Email: <a href="mailto:yongyi@wustl.edu">yongyi@wustl.edu</a>
* ORCID: <a href="https://orcid.org/0009-0004-7286-6126">0009-0004-7286-6126</a>
