---
permalink: /
title: "Joey 郭 (郭金宇)"
author_profile: true
redirect_from: 
  - /about/c
  - /about.html
---

郭金宇，电子科技大学信息与软件工程学院教师，剑桥大学联合培养博士，IEEE Member，中国中文信息学会青年
工作委员会委员，中国计算机学会自然语言处理专委会委员，中国人工智能学会会员，中国通信学会会员。主要研
究领域为人工智能、自然语言处理。研究方向是大模型在不同任务场景应用(如对话系统、智能检索问答、信息抽取
等)下的适配微调优化及大模型安全与推理加速，主要涉及技术包括指令微调、遗忘学习、检索增强生成 (RAG)、混
合专家系统 (MoE)、AI智能体、知识图谱等。目前已经以第一/通讯作者身份在国际知名会议期刊上(如CCF A类会
议、SCI一区期刊等)发表录用论文二十余篇。担任ACL、Neurips、ICML、WWW等多个国际知名会议及期刊的审稿
人，目前已经主持主研各类科研项目二十余项。


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


How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
