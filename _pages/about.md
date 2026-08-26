---
permalink: /
title: "Qi (Katherine) Wang"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
.pub-wrap { max-width: calc(100% - 205px - 2.4em); }
@media (max-width: 900px) {
  .pub-wrap { max-width: 100%; }
}
</style>

<div class="intro-grid">
<div class="intro-main">
<p>I am a Postdoctoral Associate at Boston University, Questrom School of Business. I am fortunate to be advised by <a href="https://www.bu.edu/questrom/profiles/anita-carson/">Anita Carson</a> and to work with <a href="https://www.bu.edu/questrom/profiles/chrysanthos-dellarocas/">Chris Dellarocas</a>, <a href="https://www.bu.edu/questrom/profiles/patricia-cortes/">Patricia Cortes</a>, <a href="https://www.bu.edu/questrom/profiles/william-kahn/">William Kahn</a>, and <a href="https://goizueta.emory.edu/faculty/profiles/anandhi-bharadwaj">Anandhi Bharadwaj</a> (Emory). I received my PhD through a joint doctoral program between the University of Victoria and Xi'an Jiaotong University.</p>
<p><strong style="color: #1E1E1E; font-weight: 600;">My research examines how AI transforms human expertise, work, and organizations.</strong> Grounded primarily in <strong style="color: #1E1E1E; font-weight: 600;">healthcare</strong>, I study how technologies and devices reshape care delivery, workforce dynamics, and organizational outcomes. I draw on causal inference, machine learning, natural language processing, and LLM-based methods, applied to administrative and healthcare data, at the intersection of information systems and operations management.</p>
</div>
<aside class="intro-side">
<p class="side-heading">Upcoming talks</p>
<ul class="side-list">
  <li><span class="side-name">Workshop on Empirical Research in OM (Wharton School)</span><span class="side-date">Philadelphia · Oct 1</span></li>
  <li><span class="side-name">INFORMS CIST</span><span class="side-date">San Francisco · Oct 31</span></li>
  <li><span class="side-name">INFORMS Annual Meeting</span><span class="side-date">San Francisco · Nov 2</span></li>
  <li><span class="side-name">DSI Annual Conference</span><span class="side-date">San Francisco · Nov 22</span></li>
</ul>
</aside>
</div>

{% include base_path %}

<div class="pub-wrap">

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

</div>
