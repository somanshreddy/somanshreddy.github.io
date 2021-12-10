---
layout: page
title: About
permalink: /about/
weight: 2
---

# **About Me :wave:**

Check out my <a href="https://drive.google.com/file/d/1ReNcJ3OBSsS92TOQSbum2PXcYuULdD63/view?usp=sharing">CV/Resume</a> for a quick summary of the below.

I am a backend software development engineer at Komprise. I have majored in Computer Science during my BTech at Manipal Institute of Technology. I also have a minor in Intelligent Systems which covers Machine Learning and Natural Language Processing.

Currently I am applying for a Master's in Computer Science in the US for Fall 2022.

I have recently developed an interest in learning (and using) new words to <strike>bamboozle</strike> edify my friends. For this, I would like to give credit to the GRE for being more than just another exam.

Outside of work, you would find me watching anime, cricket and basketball.

---

Please refer to the below table of contents to navigate through the rest of the page.

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
