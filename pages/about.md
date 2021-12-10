---
layout: page
title: About
permalink: /about/
weight: 2
---

# **About Me :wave:**

I am a backend software development engineer at Komprise. I will be applying for a Master's in Computer Science in the US for Fall 2022.

{% capture list_items %}
Research Interests
Experience
Programming Languages
GitHub Contributions
Upcoming features on this website
{% endcapture %}
{% include elements/list.html title="Table of Contents" type="toc" %}

<div class="row" id="research-nterests">
{% include about/research.html title="Research Interests" %}
</div>

<div class="row" id="experience">
{% include about/timeline.html title="Experience" %}
</div>

<div class="row" id="programming-languages">
{% include about/skills.html title="Programming Languages" source=site.data.programming-skills %}
<!-- {% include about/skills.html title="Other Skills" source=site.data.other-skills %} -->
</div>

<div class="row" id="github-contributions">
{% include about/github.html title="GitHub Contributions" %}
</div>

<div class="row" id="upcoming-features-on-this-website">
{% include about/upcoming_features.html title="Upcoming features on this website" %}
</div>
