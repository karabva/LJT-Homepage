---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a first-year PhD candidate at HKUST NLP Group, supervised by Professor Junxian He. I graduated from Shanghai Jiao Tong University (SJTU) in June 2024. My research focuses on natural language processing and machine learning, with specific interests in:

- LLM Reasoning and Reinforcement Learning
- Hallucination in Vision-Language Models (VLM)
- LLM truthfulness and Interpretability

## Education

- **Ph.D. in Computer Science** (2024-Present)
  - Hong Kong University of Science and Technology
  - HKUST NLP Group

- **B.Eng.** (2020-2024)
  - Shanghai Jiao Tong University

## Research Experience

- **Research Intern** (February 2025 - Present)
  - MINIMAX

- **Research Intern** (June 2024 - September 2024)
  - Tencent WXG
  - Advisor: Zifei Shan

- **Research Intern** (June 2023 - December 2023)
  - Shanghai AI Lab
  - Advisor: Prof. Yu Cheng

## Awards

- Zhiyuan Honor Scholarship, Shanghai Jiao Tong University

## Skills

- **Programming Languages**: Python, C++, Java
- **Machine Learning Frameworks**: PyTorch, TensorFlow, Hugging Face
- **Tools & Technologies**: Git, Docker, Linux, LaTeX
- **Languages**: Mandarin (Native), English (Fluent)

## Publications

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.
{% endif %}

{% include base_path %}

<!-- New style rendering if publication categories are defined -->
{% if site.publication_category %}
  {% for category in site.publication_category  %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        <h2>{{ category[1].title }}</h2><hr />
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %}

## Contact

- Email: jliugi@connect.ust.hk
- GitHub: [Vicent0205](https://github.com/Vicent0205)
- Google Scholar: [Profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
- X (Twitter): [@junteng88716710](https://twitter.com/junteng88716710)
