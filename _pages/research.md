---
layout: archive
title: "研究方向"
permalink: /research/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}

## 研究方向
1. 学术规范与评价
2. 科学计量学
3. 信息资源建设
4. AIGC / 数据管理

## 科研项目
1. 国家社科基金西部项目，创新经济学视野下的专利引用关系再认识及其评价意义再研究，2021-2022，参与
2. 四川省科技厅2021年软科学计划，成渝地区双城经济圈高校联盟科技创新协同战略研究，2022-2022，参与
3. 四川⼤学“⼤学⽣创新创业训练计划”（省级），浩气长存：红色题材记录片创新传播路径研究——基于“红色云端”大学生素质教育平台的开发推广，2021-2022，第二主研
4. 四川大学对口帮扶甘洛县“十四五规划”子课题，北凉山州旅游环线产业发展研究，2020-2021，参与
