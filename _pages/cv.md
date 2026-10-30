---
title: "CV"
layout: gridlay
permalink: /cv/
---

<header class="page-intro"><p class="eyebrow">Experience, teaching &amp; supervision</p><h1>Curriculum vitae.</h1><p class="section-lead">Connecting molecular cytoskeletal assembly with neuronal development—and building the experimental and quantitative tools to test the mechanism.</p></header>

<p><a class="btn-pill btn-pdf" href="{{ site.url }}{{ site.baseurl }}/{{ site.links.cv }}" target="_blank">Download full CV (PDF)</a></p>

<div class="section-card">
<div class="pi-card">
<img src="{{ site.url }}{{ site.baseurl }}/images/{{ site.photo }}" class="pi-photo" alt="{{ site.name }}" loading="lazy">
<div>
<h3 class="pi-name">{{ site.name }}</h3>
<p style="font-style: italic; color: var(--text-secondary);">{{ site.title }}, {{ site.institution }}</p>
<div class="pi-links">
{% if site.email %}<a href="mailto:{{ site.email }}" class="icon-link" title="Email"><i class="fa-solid fa-envelope"></i></a>{% endif %}
{% if site.links.cv and site.links.cv != "" %}<a href="{{ site.url }}{{ site.baseurl }}/{{ site.links.cv }}" class="icon-link" title="CV"><i class="ai ai-cv"></i></a>{% endif %}
{% if site.links.google_scholar and site.links.google_scholar != "" %}<a href="{{ site.links.google_scholar }}" class="icon-link" title="Google Scholar"><i class="ai ai-google-scholar"></i></a>{% endif %}
{% if site.links.github and site.links.github != "" %}<a href="{{ site.links.github }}" class="icon-link" title="GitHub"><i class="fa-brands fa-github"></i></a>{% endif %}
{% if site.links.researchgate and site.links.researchgate != "" %}<a href="{{ site.links.researchgate }}" class="icon-link" title="ResearchGate"><i class="ai ai-researchgate"></i></a>{% endif %}
{% if site.links.orcid and site.links.orcid != "" %}<a href="{{ site.links.orcid }}" class="icon-link" title="ORCID"><i class="ai ai-orcid"></i></a>{% endif %}
{% if site.links.linkedin and site.links.linkedin != "" %}<a href="{{ site.links.linkedin }}" class="icon-link" title="LinkedIn"><i class="fa-brands fa-linkedin"></i></a>{% endif %}
</div>
{% if site.data.pi[0].education %}
<ul style="margin-top: var(--space-4);">
{% for education in site.data.pi[0].education %}
<li>{{ education | replace: "-","&#8211;" }}</li>
{% endfor %}
</ul>
{% endif %}
</div>
</div>
</div>

<div class="section-card" markdown="1">
### Research experience
- **2017–present — Postdoctoral Researcher**, DZNE, Bonn (Bradke Lab). Led the experimental development and quantitative analysis of the cytoskeletal oscillator study (*Nature*, 2026). Built R/ImageJ pipelines and multidisciplinary collaborations; with Andreas Husch, re-established local single-cell perfusion.
- **2014–2017 — Postdoctoral Researcher**, ZMBH, University of Heidelberg (Schiebel Lab). First- and co-corresponding-author comparative review (*Trends Cell Biol.*, 2015); independently initiated the MOZART1 project, secured an EMBO Short-Term Fellowship, and established biochemical reconstitution of an active microtubule-nucleation template (*J. Cell Biol.*, 2016).
- **2009–2014 — Doctoral Researcher**, ZMBH, University of Heidelberg (Schiebel Lab). Phospho-regulation of γ-TuSC and its receptors; targeting of γ-tubulin complexes to microtubule organizing centers.
</div>

{% if site.data.awards %}
<div class="section-card">
<h3>Honors &amp; fellowships</h3>
<ul>
{% for award in site.data.awards %}
<li>{{ award.name | replace: "-","&#8211;" }}</li>
{% endfor %}
</ul>
</div>
{% endif %}

<div class="section-card" markdown="1">
### Invited talks (selected)
- FAU Erlangen-Nürnberg (15 October 2026)
- Microtubules in Neurons, Chiemsee (2023)
- The Cytoskeleton of Neurons and Glia, webinar series (2023)
- EMBO Workshop *Neural Development and Neurodegeneration*, Taipei (2022)
- FENS Symposium, Paris (2022)
- CSHL meeting *Molecular Mechanisms of Neuronal Connectivity*, New York (2022)
- European Cytoskeleton Forum, Hannover (2022)
- Invited lecture (with F. Bradke), NYCU College of Life Sciences, Taiwan (2022) — [watch ▶](https://www.youtube.com/watch?v=Kd7ejCS3kHg)
</div>

{% if site.data.people %}
<div class="section-card">
<h3>Student supervision</h3>
<p>Supervised three M.Sc. projects or rotations from experimental planning through quantitative interpretation and presentation. The 2025 rotation combined live imaging, pharmacological perturbation, Fiji kymographs, and R analysis to study microtubule retrograde flow.</p>
<ul>
{% for student in site.data.people %}
<li>{{ student.name }}, {{ student.location }} ({{ student.degree }}, {{ student.year }})</li>
{% endfor %}
</ul>
</div>
{% endif %}

<div class="section-card" markdown="1">
### Teaching & service
- Coordinator, M.Sc. Molecular Cell Biology EM5 practical module, University of Bonn (2023–2025).
- Teaching at Bonn: light-microscopy basics (2020, 2022), live-cell imaging (2022), and data visualization with R (2023).
- Teaching at Heidelberg: M.Sc. cell-division practical course (2013) and cell-cycle checkpoint regulation lecture (2012).
- Associate Faculty Member, H1 Connect (formerly F1000 / Faculty Opinions), since 2019.
- Professional development: EMBO Laboratory Leadership for Group Leaders (2020), Project Management for Scientists (2021), and Negotiation for Scientists (2020).
</div>
