---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
---

{% include base_path %}

<style>
.cv-list { margin-top: 0.8em; }
.cv-list li { margin-bottom: 0.5em; }
</style>

<h2 class="page__title" style="margin-bottom: 0.2em;">Education</h2>
<hr style="margin-top: 0.3em;" />
<ul class="cv-list">
  <li><strong>PhD in Environmental Sciences</strong>, University of East Anglia, UK (2018–2022)</li>
  <li><strong>MSc in Conservation Biology</strong>, University of Lisbon, Portugal (2009–2012)</li>
  <li><strong>BSc in Biology</strong>, University of Lisbon, Portugal (2006–2009)</li>
</ul>

<h2 class="page__title" style="margin-bottom: 0.2em; margin-top: 2em;">Employment</h2>
<hr style="margin-top: 0.3em;" />
<ul class="cv-list">
  <li><strong>Junior Researcher</strong>, BIOPOLIS-CIBIO, University of Porto, Portugal (2025–present)</li>
  <li><strong>Postdoctoral Fellow</strong>, French National Research Institute for Sustainable Development (IRD), France (2024–2025)</li>
  <li><strong>Postdoctoral Fellow</strong>, Tel Aviv University, Israel (2022–2024)</li>
  <li><strong>Research Associate</strong>, University of East Anglia, UK (2014–2017)</li>
  <li><strong>Research Assistant</strong>, University of East Anglia, UK (2015)</li>
  <li><strong>“Leonardo da Vinci” EU Internship</strong>, Institute for Avian Research, Germany (2014)</li>
  <li><strong>Research Assistant</strong>, University of Lisbon, Portugal (2011-2013)</li>
  <li><strong>Research Internship</strong>, University of Lisbon, Portugal (2009)</li>
</ul>

<h2 class="page__title" style="margin-bottom: 0.2em; margin-top: 2em;">Publications</h2>
<hr style="margin-top: 0.3em;" />

{% assign n_articles = site.publications | where: "category", "manuscripts" | size %}
{% assign n_preprints = site.publications | where: "category", "preprints" | size %}
{% assign n_datasets = site.publications | where: "category", "datasets" | size %}

<li>To date, I have published {{ n_articles }} peer-reviewed article{% if n_articles != 1 %}s{% endif %}{% if n_datasets > 0 %},{% else %} and{% endif %}
{{ n_preprints }} preprint{% if n_preprints != 1 %}s{% endif %}{% if n_datasets > 0 %} and {{ n_datasets }} dataset{% if n_datasets != 1 %}s{% endif %}{% endif %}.
The full list is on the <a href="{{ base_path }}/publications/">Publications</a> page.</li>

<h2 class="page__title" style="margin-bottom: 0.2em; margin-top: 2em;">Student supervision</h2>
<hr style="margin-top: 0.3em;" />
<ul class="cv-list">
  <li>I currently co-supervise two PhD students, one MRes student, and two MSc students, and have previously supervised or mentored 12 MSc and BSc students across multiple institutions</li>
</ul>

<h2 class="page__title" style="margin-bottom: 0.2em; margin-top: 2em;">Science communication</h2>
<hr style="margin-top: 0.3em;" />
<ul class="cv-list">
  <li>My work has been presented in over 40 conference presentations and featured in international news outlets, podcasts, nature documentaries, and at science communication events (see <a href="{{ base_path }}/outreach/">Outreach</a>)</li>
</ul>
