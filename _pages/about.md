---
permalink: /
title: "Qi (Katherine) Wang"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<p>Hello! I am a postdoctoral researcher at Boston University, Questrom School of Business. I am fortunate to be advised by <a href="https://www.bu.edu/questrom/profiles/anita-carson/">Anita Carson</a> and to work with <a href="https://www.bu.edu/questrom/profiles/chrysanthos-dellarocas/">Chris Dellarocas</a>, <a href="https://www.bu.edu/questrom/profiles/patricia-cortes/">Patricia Cortes</a>, <a href="https://www.bu.edu/questrom/profiles/william-kahn/">William Kahn</a>, and <a href="https://goizueta.emory.edu/faculty/profiles/anandhi-bharadwaj">Anandhi Bharadwaj</a> (Emory). I received my PhD through a joint doctoral program between the University of Victoria and Xi'an Jiaotong University.</p>

<p><strong style="color: #1E1E1E; font-weight: 600;">My research examines how AI transforms human expertise, work, and organizations.</strong> Grounded primarily in <strong style="color: #1E1E1E; font-weight: 600;">healthcare</strong>, I study how technologies and devices reshape care delivery, workforce dynamics, and organizational outcomes. I draw on causal inference, ML, NLP, and LLMs methods, applied to administrative and healthcare data, at the intersection of information systems and operations management.</p>

<p>My AI research projects have been awarded grants from the <a href="https://www.bu.edu/dbi/ai-initiative/">Business of AI Initiative</a> at Boston University's Digital Business Institute. I co-proposed <i>"AI-Enabled Organizational Learning in Healthcare"</i>, a project in collaboration with Boston-area hospitals, and work on <i>"Generative AI and the Future of Work"</i>.</p>

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
