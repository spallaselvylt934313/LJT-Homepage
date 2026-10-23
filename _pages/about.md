---
permalink: /
title: "Junteng Liu"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a first-year PhD candidate at the HKUST NLP Group, Hong Kong University of Science and Technology (HKUST), advised by Professor Junxian He. Professor Junxian He also advised me during my undergraduate studies at Shanghai Jiao Tong University (SJTU). My research focuses on natural language processing and machine learning.

## Research Interests

- LLM Reasoning and Reinforcement Learning
- Hallucination in Vision-Language Models (VLM)
- LLM Truthfulness and Interpretability

## Academic Background

- **Ph.D. in Computer Science**, Hong Kong University of Science and Technology (2024 - Present)
- **B.Eng.**, Shanghai Jiao Tong University (2020 - 2024), graduated in June 2024
- **Zhiyuan Honor Scholarship**, Shanghai Jiao Tong University

## Research Experience

- **Research Intern**, MINIMAX (February 2025 - Present)
- **Research Intern**, Tencent WXG (June 2024 - September 2024) - Advisor: Zifei Shan
- **Research Intern**, Shanghai AI Lab (June 2023 - December 2023) - Advisor: Prof. Yu Cheng

## Skills

- Natural Language Processing
- Machine Learning
- LLM Reasoning and Reinforcement Learning
- Hallucination in Vision-Language Models (VLM)
- LLM Truthfulness and Interpretability

## Publications

{% include base_path %}
{% for pub in site.publications %}
{% if pub.order %}
<article class="archive__item">
  <h3 class="archive__item-title"><a href="{{ base_path }}{{ pub.url }}">{{ pub.title }}</a></h3>
  <p>{{ pub.authors }}</p>
  <p><i>{{ pub.venue }}</i>, {{ pub.year }}{% if pub.role %} &middot; {{ pub.role }}{% endif %}{% if pub.code %} &middot; Code repository: {{ pub.code }}{% endif %}</p>
</article>
{% endif %}
{% endfor %}

## Contact

- Email: <jliugi@connect.ust.hk>
- GitHub: <https://github.com/Vicent0205>
- Google Scholar: <https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate>
- X (Twitter): [@junteng88716710](https://twitter.com/junteng88716710)
