---
permalink: /
title: "郭金宇"
author_profile: true
lang: zh
redirect_from: 
  - /about/c
  - /about.html
---

郭金宇，电子科技大学信息与软件工程学院讲师，剑桥大学信息工程系联合培养博士，中国中文信息学会青年工作委员会委员，中国中文信息学会大模型与生成专委会委员，中国计算机学会自然语言处理专委会委员。主要研究领域为自然语言处理、信息检索、多模态学习、具身智能等。研究方向是大模型在不同场景下的适配微调优化及大模型安全与加速。目前已经在国际知名会议期刊上(如 CCF A 类会议、SCI 一区期刊等)发表录用论文四十余篇，其中以第一/通讯作者身份发表录用论文26篇。担任ACL、NeurIPS、ICML、WWW、TKDE等多个国际知名会议及期刊的审稿人，目前已经主持主研国资计划、四川省自然科学基金青年基金、国家重点实验室开放基金等多个国家级及省部级科研项目。




论文发表（部分）
======
<!-- <ul>
{% for p in site.publications_ %}
  <li>
    <strong>{{ p.title }}</strong><br/>
    {{ p.authors }} {{ p.venue }}{% if p.desc_zh %} ({{ p.desc_zh }}){% endif %}
  </li>
{% endfor %}
</ul> -->

<ul>
{% for p in site.publications_ %}
  <li>
    <strong>{{ p.title }}</strong><br/>
    {{ p.authors | markdownify | replace: "<p>", "" | replace: "</p>", "" }} {{ p.venue }}
    {% if page.lang == "en" %}
      {% if p.desc_en %} <strong>({{ p.desc_en }})</strong>{% endif %}
    {% else %}
      {% if p.desc_zh %} <strong>({{ p.desc_zh }})</strong>{% endif %}
    {% endif %}
  </li>
{% endfor %}
</ul>




学术服务
======
1. 中国中文信息学会青年工作委员会委员
2. 中国中文信息学会大模型与生成专委会委员
3. 中国计算机学会自然语言处理专委会委员
4. 担任 ICML、NeurIPS、ACL、WWW、AAAI、EMNLP、TKDE、NAACL、TMM、AISTATS、Information Fusion、Information Processing & Management 等多个国际知名会议及期刊的审稿人及PC Member


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

| 荣誉 | 
|------|
| 2024年北京市优秀博士毕业生|
| 2022年博士国家奖学金 |
| 2024年北京邮电大学优秀博士毕业生 |
| 2020年国家重点实验室优秀博士研究生|
