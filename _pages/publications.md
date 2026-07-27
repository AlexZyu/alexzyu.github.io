---
layout: archive
title: "发表论文"
permalink: /publications/
author_profile: true
lang: zh
translation_url: /en/publications/
title_en: "Publications"
translation_key: "page-publications"
body_en: |
  ## Acknowledged Contributions
  
  In addition to the publications listed above, I contributed to the following papers. Although I was not formally listed as an author for various reasons, my contributions were acknowledged in the acknowledgements section.
  
  [1] Zhao, L. (2024). Digitally Representing Places: The Reproduction of Destination Images through Video Big Data. *Journal of Guizhou Minzu University (Philosophy and Social Sciences)*, (3), 132-147.
  
  [2] Ye, J. (2025). Exploring the Concept of Information Resources and Its Logical Relationships with Information, Data, Knowledge, and Related Concepts. *Journal of the China Society for Scientific and Technical Information*, 44(1), 93-102.
  
  [3] Ye, J. (2025). Problems and Approaches in Developing a Chinese-Style Evaluation System for Philosophy and Social Sciences from the Perspective of the All-round Evaluation of Research. *Library Work and Study*, (1), 5-15.
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


## 受到致谢

除上述已署名的论文外，本人还参与了以下论文的工作。虽然由于各种原因未被正式列为作者，但已在致谢部分得到认可。

[1] 赵靓.数志地方：视频大数据的目的地形象再生产[J].贵州民族大学学报(哲学社会科学版),2024,(3):132-147.

[2] 叶继元.信息资源的概念及其与信息、数据、知识等概念逻辑关系探讨[J].情报学报,2025,44(1):93-102.

[3] 叶继元.学术“全评价”视域下中国特色哲学社会科学评价体系建设的问题与思路[J].图书馆工作与研究,2025,(1):5-15.
