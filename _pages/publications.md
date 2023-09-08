---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

### **Conference**
**2023**
- **C12**. [Accel-GCN: High-Performance GPU Accelerator Design for Graph Convolution Networks](https://arxiv.org/abs/2308.11825)\
Xi Xie*, **Hongwu Peng***, Amit Hasan, ... Tong Geng, Omer Khan, Caiwen Ding\
*2023 IEEE/ACM International Conference On Computer Aided Design* (**ICCAD**), 2023


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
