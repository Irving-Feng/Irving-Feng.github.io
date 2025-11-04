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
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a first-year CS PhD student at [Zhejiang University (浙江大学)](https://www.zju.edu.cn/), supervised by Prof. [Huajun Chen](https://person.zju.edu.cn/en/huajun). Before that, I received my B.S. degree in the Turing Elite class at [Xidian University (西电)](https://www.xidian.edu.cn/) in 2024, majoring in Artificial Intelligence. My research interests revolve around Large Language Models (LLMs), with a particular focus on LLM evaluation and reasoning.

During May 2023 to Sept 2023, I worked as a research intern at SJTU [GAIR Lab](https://plms.ai/) under the guidance of Prof. [Pengfei Liu](http://pfliu.com/), where I focused on various aspects of Large Language Models (LLMs), primarily on the evaluation and reasoning of LLMs.

<a href='https://scholar.google.com/citations?user=PQVboTgAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>


# 🔥 News
- *2025.10*: &nbsp;🎉🎉 I was awarded the **National Scholarship** (国家奖学金) for PhD Students during the first year of my doctoral studies.
- *2025.07*: &nbsp;🎉🎉 One co-authored paper (*FacTool*) is accepted by COLM 2025!
- *2025.05*: &nbsp;🎉🎉 Three papers are accepted by ACL 2025! 
- *2025.02*: &nbsp;🎉🎉 One paper is accepted by ICLR 2025! 
- *2025.01*: &nbsp;🎉🎉 One survey paper about [Scientific Large Language Models](https://github.com/HICAI-ZJU/Scientific-LLM-Survey) is accepted by ACM Computing Surveys!

# 📝 Publications 

(* indicates equal contribution)
 
## Preprint
<div class='paper-box-text' markdown="1">
<font color="CornFlowerBlue">CoT-Evo: Evolutionary Distillation of Chain-of-Thought for Scientific Reasoning
</font>
**Kehua Feng\***, Keyan Ding\*, Zhihui Zhu, Lei Liang, Qiang Zhang, Huajun Chen\\
**Preprint, 2025** |  [PDF](https://arxiv.org/pdf/2510.13166)
</div>

<div class='paper-box-text' markdown="1">
<font color="CornFlowerBlue">Learning an Efficient Multi-Turn Dialogue Evaluator from Multiple Judges
</font>
Yuqi Tang, **Kehua Feng**, Yunfeng Wang, Zhiwen Chen, Chengfei Lv, Gang Yu, Qiang Zhang, Keyan Ding\\
**Preprint, 2025** |  [PDF](https://arxiv.org/pdf/2508.00454) | [Code](https://arxiv.org/pdf/2508.00454)
</div>

<div class='paper-box-text' markdown="1">
<font color="CornFlowerBlue">SciCUEval: A Comprehensive Dataset for Evaluating Scientific Context Understanding in Large Language Models
</font>
Jing Yu, Yuqi Tang, **Kehua Feng**, Mingyang Rao, Lei Liang, Zhiqiang Zhang, Mengshu Sun, Wen Zhang, Qiang Zhang, Keyan Ding, Huajun Chen\\
**Preprint, 2025** |  [PDF](https://arxiv.org/pdf/2505.15094) | [Code](https://github.com/HICAI-ZJU/SciCUEval) | [HF Repo](https://huggingface.co/datasets/hicai-zju/SciCUEval)
</div>

<div class='paper-box-text' markdown="1">
<font color="CornFlowerBlue">ERPO: Advancing Safety Alignment via Ex-Ante Reasoning Preference Optimization
</font>
**Kehua Feng\***, Keyan Ding\*, Jing Yu, Menghan Li, Yuhao Wang, Tong Xu, Xinda Wang, Qiang Zhang, Huajun Chen\\
**Preprint, 2025** |  [PDF](https://arxiv.org/pdf/2504.02725)
</div>


## Conference

<div class='paper-box-text' markdown="1">
<font color="CornFlowerBlue">FacTool: Factuality Detection in Generative AI--A Tool Augmented Framework for Multi-Task and Multi-Domain Scenarios
</font>
I-Chun Chern, Steffi Chern, Shiqi Chen, Weizhe Yuan, **Kehua Feng**, Chunting Zhou, Junxian He, Graham Neubig, Pengfei Liu\\
**COLM 2025** |  [PDF](https://arxiv.org/abs/2307.13528) | [Code](https://github.com/GAIR-NLP/factool)
</div>

<div class='paper-box-text' markdown="1">
<font color="CornFlowerBlue">Sample-Efficient Human Evaluation of Large Language Models via Maximum Discrepancy Competition
</font>
**Kehua Feng\***, Keyan Ding\*, Hongzhi Tan, Kede Ma, Zhihua Wang, Shuangquan Guo, Yuzhou Cheng, Ge Sun, Guozhou Zheng, Qiang Zhang, Huajun Chen\\
**ACL 2025, Main** |  [PDF](https://arxiv.org/pdf/2404.08008) | [Code](https://github.com/weiji-Feng/MAD-Eval)
</div>

<div class='paper-box-text' markdown="1">
<font color="CornFlowerBlue">Enhancing Safe and Controllable Protein Generation via Knowledge Preference Optimization
</font>
Yuhao Wang, Keyan Ding, **Kehua Feng**, Zeyuan Wang, Ming Qin, Xiaotong Li, Qiang Zhang, Huajun Chen\\
**ACL 2025, Main** |  [PDF](./) | [Code](https://github.com/HICAI-ZJU/KPO)
</div>

<div class='paper-box-text' markdown="1">
<font color="CornFlowerBlue">Boosting LLM’s Molecular Structure Elucidation with Knowledge Enhanced Tree Search Reasoning
</font>
Xiang Zhuang, Bin Wu, Jiyu Cui, **Kehua Feng**, Xiaotong Li, Huabin Xing, Keyan Ding, Qiang Zhang, Huajun Chen\\
**ACL 2025, Main** |  [PDF](https://arxiv.org/pdf/2506.23056) | [Code](https://github.com/HICAI-ZJU/K-MSE)
</div>

<div class='paper-box-text' markdown="1">
<font color="CornFlowerBlue">SaMer: A Scenario-aware Multi-dimensional Evaluator for Large Language Models
</font>
**Kehua Feng\***, Keyan Ding\*, Jing Yu, Yiwen Qu, Zhiwen Chen, Gang Yu, Qiang Zhang, Huajun Chen\\
**ICLR 2025** |  [PDF](https://openreview.net/pdf?id=aBnVU5DL3I) | [Code](https://github.com/Irving-Feng/SaMer)
</div>

<div class='paper-box-text' markdown="1">
<font color="CornFlowerBlue">SciKnowEval: Evaluating Multi-level Scientific Knowledge of Large Language Lodels
</font>
**Kehua Feng\***, Keyan Ding\*, Weijie Wang\*, Xiang Zhuang, Zeyuan Wang, Ming Qin, Yu Zhao, Jianhua Yao, Qiang Zhang, Huajun Chen\\
**NeurIPS Workshop, 2025** |  [PDF](https://arxiv.org/pdf/2406.09098) | [Code](https://github.com/hicai-zju/sciknoweval) | [Page](http://www.scimind.ai/sciknoweval/) | [HF Repo](https://huggingface.co/datasets/hicai-zju/SciKnowEval)
</div>

## Journal

<div class='paper-box-text' markdown="1">
<font color="CornFlowerBlue">Scientific Large Language Models: A Survey on Biological & Chemical Domains
</font>
Qiang Zhang, Keyan Ding, Tianwen Lv, Xinda Wang, Qingyu Yin, Yiwen Zhang, Jing Yu, Yuhao Wang, Xiaotong Li, Zhuoyi Xiang, **Kehua Feng**, Xiang Zhuang, Zeyuan Wang, Ming Qin, Mengyao Zhang, Jinlu Zhang, Jiyu Cui, Renjun Xu, Hongyang Chen, Xiaohui Fan, Huabin Xing, Huajun Chen\\
**ACM Computing Surveys, 57 (6), 2025** |  [PDF](https://arxiv.org/pdf/2401.14656) | [Code](https://github.com/HICAI-ZJU/Scientific-LLM-Survey)
</div>


# 🎖 Honors and Awards
- National Scholarship for PhD Students (国家奖学金, top 5%), *2025.10*,
- Song Qingling Future Scholarship (宋庆龄未来奖学金), *2023.12*,
- *__Finalist Winner__ (1st Prize, top 1.5%)*, The International Mathematical Contest in Modeling (MCM/ICM), *2023.05*,
- *__1st price__*, The China Undergraduate Mathematical Contest in Modeling (CUMCM) in Shaanxi Province, *2022.12*,
- *__1st price__*, The Chinese Mathematics Competitions (CMC) in Shaanxi Province, *2021.12*,

# 📖 Educations
- *2024.09 - now*, &nbsp;&nbsp;&nbsp;  Ph.D., Computer science and technology, Zhejiang University.
- *2020.09 - 2024.06*, B.S., Turing Elite Class, Artificial Intelligence, Xidian University.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2024.04 - 2025.03*, Alibaba Taobao and Tmall Group, Hangzhou, China.
