---
permalink: /en/
title: "Joey Guo"
author_profile: true
lang: en
---

{% include base_path %}

Welcome to my English homepage!

This is a test English version of my personal site.


Joey Guo is a Lecturer at the University of Electronic Science and Technology of China (UESTC) and a joint Ph.D. trainee with the University of Cambridge. He is a member of the Youth Working Committee of the Chinese Information Processing Society of China (CIPSC), a member of the CIPSC Committee on Large Models and Generation, a member of the CCF Technical Committee on Natural Language Processing, and a member of both the Chinese Association for Artificial Intelligence (CAAI) and the China Communications Society.

His main research areas are artificial intelligence and natural language processing. His current research focuses on efficient adaptation and fine-tuning of large language models for different task scenarios, acceleration of large model inference, data governance for large models, and large model safety. He has published more than twenty papers as first or corresponding author in well-known international conferences and journals (including CCF Tier-A conferences and SCI Q1 journals). He serves as a reviewer for several top conferences and journals such as ACL, NeurIPS, ICML, WWW, and TKDE, and has led or played a key role in more than twenty research projects.




Articles and journals (partial list)
======
<ul>
{% for p in site.publications_ %}
  <li>
    <strong>{{ p.title }}</strong><br/>
    {{ p.authors }} {{ p.venue }}{% if p.desc_en %} ({{ p.desc_en }}){% endif %}
  </li>
{% endfor %}
</ul>

Academic services
======
Serves as a reviewer for numerous internationally renowned conferences and journals, including ICML, NeurIPS, ACL, WWW, AAAI, EMNLP, TKDE, NAACL, AISTATS, Information Fusion, Information Processing & Management, and ESWA.


Partial Project Experience
------

| Project                                                                                    |            Period | Role           |
| ------------------------------------------------------------------------------------------ | ----------------: | -------------- |
| 2025 State-owned Assets Plan (Category C)                                                  | 2025-07 – present | PI             |
| 16th Batch Fundamental Research Funds for the Central Universities Project                 | 2025-04 – present | PI             |
| UESTC–Kunpeng Ascend Sci-Tech Innovation Incubation Center Innovation Project (Category A) | 2025-09 – present | PI             |
| 2022 Beijing Natural Science Foundation General Program                                    | 2022-08 – 2024-12 | Key researcher |



Honors
------

| Honors | Time |
|------|-----:|
| Outstanding Doctoral Graduates of Beijing in 2024 | 2024-05 |
| 2022 National Scholarship for Doctoral Students | 2022-12 |

