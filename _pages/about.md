---
permalink: /
title: "郭金宇"
author_profile: true
lang: zh
redirect_from: 
  - /about/c
  - /about.html
---

---
title: "Joey Guo"
permalink: /en/
lang: en
author_profile: true
---

郭金宇，电子科技大学，讲师，剑桥大学联合培养博士，中国中文信息学会青年
工作委员会委员，中国中文信息学会大模型与生成专委会委员，中国计算机学会自然语言处理专委会委员，中国人工智能学会会员，中国通信学会会员。
主要研究领域为人工智能、自然语言处理。研究方向是大模型在不同任务场景下的适配微调优化、大模型推理加速、大模型数据治理及大模型安全。
目前已经以第一/通讯作者身份在国际知名会议期刊(如CCF A类会议、SCI一区期刊等)发表录用论文二十余篇。担任ACL、NeurIPS、ICML、WWW、TKDE等多个国际知名会议及期刊的审稿人，目前已经主持主研各类科研项目二十余项1。




论文/期刊
======
{% for y in site.publications_by_year %}
  <h2>{{ y.year }}</h2>
  <ul>
  {% for p in y.items %}
    <li><strong>{{ p.title }}</strong><br/>
        {{ p.authors }}<br/>
        <em>{{ p.venue }}</em> ({{ p.year }})
    </li>
  {% endfor %}
  </ul>
{% endfor %}

学术服务
======
担任 ICML、NeurIPS、ACL、WWW、AAAI、EMNLP、TKDE、NAACL、AISTATS、Information Fusion、Information
Processing & Management、ESWA 等多个国际知名会议及期刊的审稿⼈


部分项目经历
------

| 项目 | 时间 | 角色 |
|------|-----:|
| 2025年国资计划（C） | 2025-07 至今 | 主持 |
| 第16批中央高校基本科研业务费项目 | 2025-04 至今 | 主持 |
| 电子科技大学-鲲鹏昇腾科教创新孵化中心创新课题 A类 | 2025-09 至今 | 主持 |
| 2022年北京市自然科学基金面上项目 | 2022-08 - 2024-12 | 主研 |


曾获荣誉
------

| 荣誉 | 时间 |
|------|-----:|
| 2024年北京市优秀博士毕业生 | 2024-05 |
| 2022年博士国家奖学金 | 2022-12 |

