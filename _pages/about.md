---
permalink: /
title: "Hi!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Postdoctoral Associate at Boston University, Questrom School of Business, advised by Prof. [Anita Carson](https://www.bu.edu/questrom/profiles/anita-carson/). I am also grateful to work with Professors [Chris Dellarocas](https://www.bu.edu/questrom/profiles/chrysanthos-dellarocas/), [Patricia Cortes](https://www.bu.edu/questrom/profiles/patricia-cortes/), [William Kahn](https://www.bu.edu/questrom/profiles/william-kahn/), and [Anandhi Bharadwaj](https://goizueta.emory.edu/faculty/profiles/anandhi-bharadwaj) (Emory). I received my PhD through a joint doctoral program between the University of Victoria and Xi'an Jiaotong University.

My research examines how artificial intelligence (AI) is transforming work and organizations. Grounded in healthcare, I study how health AI is reshaping care delivery, workforce dynamics, and health outcomes. I draw on causal inference, machine learning, natural language processing (NLP), and LLM-based methods, applied to large-scale administrative and healthcare data, at the intersection of information systems and operations management.

{% include base_path %}

<h2 class="pub-category-title">Publications and Submitted Papers</h2>
{% assign submitted = site.publications | where: "category", "submitted" | sort: "pub_number" %}
{% for post in submitted %}
  {% include archive-single.html %}
{% endfor %}

<h2 class="pub-category-title">Working Papers</h2>
{% assign working = site.publications | where: "category", "working" | sort: "pub_number" %}
{% for post in working %}
  {% include archive-single.html %}
{% endfor %}

<h2 class="pub-category-title">Works in Progress</h2>
{% assign wip = site.publications | where: "category", "wip" | sort: "pub_number" %}
{% for post in wip %}
  {% include archive-single.html %}
{% endfor %}

<h2 class="pub-category-title">Publications in Business Analytics</h2>
{% assign analytics = site.publications | where: "category", "analytics" | sort: "pub_number" %}
{% for post in analytics %}
  {% include archive-single.html %}
{% endfor %}
