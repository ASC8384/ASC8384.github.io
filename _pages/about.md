---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "<https://cdn.jsdelivr.net/gh/>" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "<https://raw.githubusercontent.com/>" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

<!--Hello All! My name is Tao Sun.-->

I am a first-year master's student at Beihang University in the School of Computer Science and Engineering, working with [Dr. Jian Yang](https://scholar.google.com/citations?user=i9opWEgAAAAJ) and [Prof. Zhoujun Li](https://scholar.google.com/citations?user=e-4LoEcAAAAJ).

My research centres on Natural Language Processing (NLP), specifically emphasizing large language models (LLM). I am particularly fascinated by the potential of these models and their application in advancing the field of Artificial General Intelligence (AGI). Currently, I am doing some interesting research work to explore the following areas:

- **Code LLM**: My research focuses on integrating executable code with LLMs or large multimodal models. The ultimate goal is to transform LLMs into compilers of natural language, enabling them to execute specific tasks through code or agents.
- **Code Self-Evolution**: I am exploring the potential for code to self-evolve using LLM. The ultimate aim is to enable software systems to autonomously update, optimize, and repair themselves without human intervention, thereby enhancing the efficiency and sustainability of software maintenance and development.

Looking ahead, I am actively seeking a Summer Internship for 2024 and a Ph.D. position in the field of NLP/LLM, starting in the Fall of 2026. If you are interested in my research or are open to potential collaboration, please feel free to let me know.

<!--[CV](assets/pdf/Resume_ST.pdf) / [中文简历](assets/pdf/CV_ST_ZH.pdf)-->

<!-- a href='./assets/pdf/Resume_ST.pdf'><img src="https://img.shields.io/badge/-Sun's%20Resum%C3%A9-299DE7?logo=gitbook&logoColor=white"></a> / <a href='./assets/pdf/CV_ST_ZH.pdf'><img src="https://img.shields.io/badge/-%E4%B8%AD%E6%96%87%E7%AE%80%E5%8E%86%EF%BC%88Chinese%20CV%EF%BC%89-%3Flogo%3Dgitbook%26logoColor%3Dwhite"></a-->

<!--
My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).
-->

# 🔥 News

- *2024.05*: &nbsp;🎉🎉 **UniCoder** paper is accepted by ACL 2024.
<!-- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. -->

# 📝 Publications & Papers in Preparation

<!--
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
</div>
</div>
-->

<div class='paper-box-text' markdown="1">
<strong><font color="#374798">UniCoder: Scaling Code Large Language Model via Universal Code.</font></strong>\\
**Tao Sun\***, Linzheng Chai\*, Jian Yang\*, Yuwei Yin, Hongcheng Guo, Jiaheng Liu, Bing Wang, Liqun Yang, Zhoujun Li, (*=equal contribution). \\
**ACL 2024 Main Conference** | **arXiv 2406.16441**
</div><br>

<div class='paper-box-text' markdown="1">
<strong><font color="#374798">Neural Distinguishers on TinyJAMBU-128 and GIFT-64.</font></strong>\\
**Tao Sun**, Dongsu Shen, Saiqin Long, Qingyong Deng, Shiguo Wang. \\
**ICONIP 2022 Oral**
</div><br>

<div class='paper-box-text' markdown="1">
<strong><font color="#374798">McEval: Massively Multilingual Code Evaluation.</font></strong>\\
Linzheng Chai\*, Shukai Liu\*, Jian Yang\*, Yuwei Yin, Ke Jin, Jiaheng Liu, **Tao Sun**, Ge Zhang, Changyu Ren, Hongcheng Guo, Zekun Wang, Boyang Wang, Xianjie Wu, Bing Wang, Tongliang Li, Liqun Yang, Sufeng Duan, Zhoujun Li, (*=equal contribution). \\
**arXiv 2406.07436** | [Post by PaperWeekly](https://mp.weixin.qq.com/s/j8QhH3QAf2GTSKffZV-DvQ), [a Top AI media in China](http://www.paperweekly.info/)
</div><br>

<div class='paper-box-text' markdown="1">
<strong><font color="#374798">xCOT: Cross-lingual Instruction Tuning for Cross-lingual Chain-of-Thought Reasoning.</font></strong>\\
Linzheng Chai, Jian Yang, **Tao Sun**, Hongcheng Guo, Jiaheng Liu, Bing Wang, Xiannian Liang, Jiaqi Bai, Tongliang Li, Qiyao Peng, Zhoujun Li. \\
**arXiv 2401.07037**
</div><br>

<div class='paper-box-text' markdown="1">
<strong><font color="#374798">RoleAgent: Building, Interacting, and Benchmarking High-quality Role-Playing Agents from Script.</font></strong>\\
Jiaheng Liu\*, Zehao Ni\*, Haoran Que\*, **Tao Sun**, Zekun Wang, Jian Yang, Jiakai Wang, Hongcheng Guo, Zhongyuan Peng, Ge Zhang, Jiayi Tian, Xingyuan Bu, Ke Xu, Wenge Rong, Junran Peng, Zhaoxiang Zhang, (*=equal contribution). \\
**Under Review**
</div><br>

<div class='paper-box-text' markdown="1">
<strong><font color="#374798">REALM: RAG-Driven Enhancement of Multimodal Electronic Health Records Analysis via Large Language Models.</font></strong>\\
Yinghao Zhu\*, Changyu Ren\*, Shiyun Xie, Shukai Liu, Hangyuan Ji, Zixiang Wang, **Tao Sun**, Long He, Zhoujun Li, Xi Zhu, Chengwei Pan, (*=equal contribution). \\
**arXiv 2402.07016**
</div><br>

<div class='paper-box-text' markdown="1">
<strong><font color="#374798">SVIPTR: Fast and Efficient Scene Text Recognition with Vision Permutable Extractor.</font></strong>\\
Xianfu Cheng, Weixiao Zhou, Xiang Li, Jian Yang, Hang Zhang, **Tao Sun**, Wei Zhang, Yuying Mai, Tongliang Li, Xiaoming Chen, Zhoujun Li. \\
**Under Review**
</div><br>

<div class='paper-box-text' markdown="1">
<strong><font color="#374798">XFormParser: Semi-structured Form Parser with Multimodal and Multilingual Knowledge.</font></strong>\\
Xianfu Cheng\*, Hang Zhang\*, Jian Yang, Xiang Li, Weixiao Zhou, Kui Wu, Fei Liu, Wei Zhang, **Tao Sun**, Tongliang Li, Zhoujun Li, (*=equal contribution). \\
**arXiv 2405.17336**
</div><br>

<!-- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**-->

# 🎖 Honors and Awards

- *2021* Pacemaker to Merit Student (Awarded by Xiangtan University, Top 2‰ in School)
- *2022* The Jingdong Scholarship (Awarded by Jingdong Inc.)
- *2020 & 2021 & 2022* The First Prize Scholarship (Awarded by Xiangtan University, Top 7% in School)
- *2021.10* Bronze Medal of 2021 ICPC Asia Regional Contest (Awarded by [ICPC Foundation](https://icpc.foundation))
- *2021.06* Silver Medal of 2021 CCPC National Invitational Contest (Awarded by [Committee for CCPC](https://ccpc.io/))
- *2021.11* Bronze Medal of 2021 CCPC Guilin Site Contest (Awarded by [Committee for CCPC](https://ccpc.io/))
- *2021.10* The First Prize of [China Undergraduate Mathematical Contest in Modeling](https://en.csiam.org.cn/) in Hunan Division (Awarded by [CSIAM](https://en.csiam.org.cn))

# 📖 Educations

- *2023.09 - 2026.01 (expected)*, Beihang University (BUAA), M.S. in Computer Technology, School of Computer Science and Engineering
- *2019.09 - 2023.06*, Xiangtan University (XTU), B.E. in Computer Science and Technology, School of Computer Science, GPA: 3.695 / 4.0, Rank: 2 / 88

<!--
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)
-->

# 💻 Internships

- *2024.03 — Now*, [Meituan Inc.](https://www.meituan.com/en-US/about-us), China.
  - Position: Research Intern (Full-time, Onsite, Paid)
  - Duty: Conducted research and testing on Meituan's in-house large-scale models, primarily focusing on enhancing the code expert model's capabilities in code repository-level completion and repair. Explored the application of large models in the field of software engineering, including their abilities in handling long texts and code planning and testing.
- *2022.10 — 2023.05*, [Shenzhen Intelligent Strong](http://www.ai-strong.com/), Shenzhen, China.
  - Position: Research Intern (Full-time, Onsite, Paid)
  - Duty: Conducted a financial Named Entity Recognition project from dataset construction to model optimization and deployment, achieving a 10.09% increase in F1.
