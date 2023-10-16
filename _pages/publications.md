---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Papers
* PlatoLM: Teaching LLMs via a Socratic Questioning User Simulator
* arxiv: https://arxiv.org/abs/2308.11534v4
* code: https://github.com/FreedomIntelligence/PlatoLM
* model: https://huggingface.co/FreedomIntelligence/PlatoLM-7B
  * has achieved SOTA performance from 2023/08 to 2023/10 in Alpaca-Eval and MT-Bench.  
* dataset: https://huggingface.co/datasets/FreedomIntelligence/SocraticChat
