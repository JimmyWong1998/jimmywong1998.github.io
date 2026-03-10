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

# ℹ️ About me

Junpei Huang is a fourth-year Ph.D. student at the School of Microelectronics, University of Science and Technology of China (USTC), supervised by Prof. [Yinhe Han](https://scholar.google.com/citations?user=t40cM-4AAAAJ&hl=zh-CN&oi=sra). He works closely with Prof. [Ying Wang](https://scholar.google.com/citations?user=5LoFPSQAAAAJ&hl=zh-CN&oi=ao) and Prof. [Yiming Gan](https://scholar.google.com/citations?user=d-1MZhIAAAAJ&hl=zh-CN&oi=ao). During his Ph.D. studies, he has conducted research at Center for Intelligent Computing Systems, National Key Laboratory of Processors, Institute of Computing Technology, Chinese Academy of Sciences (CICS@ICT, CAS) as a joint PhD student.

He has been deeply involved in the design and testing of the Dadu-Eye deep-learning edge processor, funded by the CAS Strategic Priority Research Program, as well as the design and validation of the “Zhejiang” Big Chip, supported by National Key Research and Development Program of China.

His research interest includes multi-chiplet memory architecture design, with an emphasis on cache coherence, IO chiplets, and scalable memory subsystems. He has published about 6 papers on chiplet designs and AI accelerators
<a href="https://scholar.google.com/citations?user=R6GxAr0AAAAJ&hl=zh-CN" target="_blank" rel="noopener" style="text-decoration:none;">
  📚
</a>
and have 2 papers under review.

# 📖 Educations
- 2016.09 - 2020.07, **University of Electronic Science and Technology of China (UESTC)**, Chengdu, Sichuan, China
  - B.Eng in Electronic and Science Technology, GPA: 3.93/4.0, Ranking: Top 10%
- 2018.09 - 2020.07, **University of Birmingham (UoB)**, Birmingham, United Kingdom
  - B.Eng in Electronic and Electrical Engineering (2+2 Joint Bachelor's Degree Program), GPA: 4.25/4.25, Ranking: First Class
- 2020.09 - 2026 (now), **University of Science and Technology of China (USTC)**, Anhui, Hefei, China
  - PhD Student in Electronic and Science Technology, GPA: 3.88/4.3

# 🔥 News (Related to my first-author publications)
- *2026.03*: &nbsp;🎉 HybridIO: Enabling Bandwidth-Aware Memory Access Offloading for Multi-Chiplet Systems with CXL-Based Hybrid Memory received first-round reviews from CAL 2026 (2× Accept, 1× Revise & Resubmit).
- *2026.02*: &nbsp;🎉🎉 SAP: Shared-Aware Prefetching for Reducing Inter-Chiplet Data Access Latency was accepted to CAL 2026.
- *2025.08*: &nbsp;🎉🎉 FlexIO: A Scalable IO Chiplet Architecture with Flexible Memory Controller Mapping was accepted to ICCD 2025.

# 📝 Publications 

## ✍️ First-author papers:

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCD 2025</div><img src='images/iccd_pre.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FlexIO: A Scalable IO Chiplet Architecture with Flexible Memory Controller Mapping](https://ieeexplore.ieee.org/abstract/document/11311086/)

**Junpei Huang**, Haobu Xu, Ying Wang, Yinhe Han. **ICCD 2025**
- Oral presentation at The University of Texas at Dallas, 11:30 - 13:00 CST, Wednesday, November 12. 
</div>
</div>

- [SAP: Shared-Aware Prefetching for Reducing Inter-Chiplet Data Access Latency](https://ieeexplore.ieee.org/abstract/document/11365544), **Junpei Huang**, Haobo Xu, Yiming Gan, et al. **CAL 2026**

## ✍️ Under review papers:

- [HybridIO: Enabling Bandwidth-Aware Memory Access Offloading for Multi-Chiplet Systems with CXL-Based Hybrid Memory](https://ieeexplore.ieee.org/abstract/document/11365544), **Junpei Huang**, Haobo Xu, Yiming Gan, et al. **CAL 2026**
- [SmartFlexIO: A Flexible IO chiplet architecture with Smart memory controller mapping for large-scale chiplet-based system](https://ieeexplore.ieee.org/abstract/document/11365544), **Junpei Huang**, Yigeng He, Ying Li, et al. **TCAD 2026**

## ✍️ Co-author papers:

- [The big chip: Challenge, model and architecture](https://ieeexplore.ieee.org/abstract/document/11365544), Yinhe Han,Haobo Xu, Meixuan Lu, Haoran Wang, **Junpei Huang**, et.al. **FR 2024**
- [The Decomposition and Combination Paradigms of Chiplet-Based Integrated Chips](https://ieeexplore.ieee.org/abstract/document/11365544), Fuping Li,Ying Wang, Meixuan Lu, Yutong Zhu, Haoran Wang, Zhun Zhao, **Junpei Huang**, et.al. **ICS 2024**
- [Toward efficient computing for robotics: From a circuit and system view](https://ieeexplore.ieee.org/abstract/document/11365544), Haobo Xu,Yuxin Yang, Feng Min, **Junpei Huang**, et.al. **TCAS-II 2022**
- [Dadu-SV: Accelerate Stereo Vision Processing on NPU](https://ieeexplore.ieee.org/abstract/document/11365544), Feng Min,Ying Yang, Haobo Xu, **Junpei Huang**, et.al. **ESL 2022**
- [Space-based Computing Chips: Current Status, Trends and Key Technique](https://ieeexplore.ieee.org/abstract/document/11365544), Xiaotong Wei,Haobo Xu, Chundi Yin, **Junpei Huang**, et.al. **JEIT 2025**

# 🔬 Research Topics

## 🧩 Chiplet Systems
<p style="text-align:center; margin:10px 0;">
  <img src="images/topic1.png" alt="Chiplet Systems"
       style="max-width:92%; height:auto; border-radius:10px;">
</p>
<p>
  <!-- TODO: 写 chiplet 的文字说明 -->
  I work on multi-chiplet memory architectures, focusing on IO chiplets, memory controller mapping, and scalable interconnect/coherence support. I am also interestin at machine learning-driven optimization/design space exploration(DSE) for hardware.
</p>
<ul>
  <li><!-- TODO --> Key directions: heuristic-based memory controller mapping / learning-based memory controller mapping / DDR- and CXL- hybrid memory system and scheduling / inter-chiplet prefetching </li>
  <li><!-- TODO --> Methods: Gem5 + DRAMSim3 + DSNet</li>
</ul>

<hr style="margin:18px 0; opacity:0.2;">

## 🧠 AI Accelerators
<p style="text-align:center; margin:10px 0;">
  <img src="images/topic2.png" alt="AI Accelerators"
       style="max-width:92%; height:auto; border-radius:10px;">
</p>
<p>
  <!-- TODO: 写 AI accelerator 的文字说明 -->
  I explore efficient AI accelerator architectures, including dataflow/memory hierarchy co-design and system-level optimizations for emerging workloads.
</p>
<ul>
  <li><!-- TODO --> Key directions: NPU/vision chips, throughput/W, dataflow</li>
  <li><!-- TODO --> Methods: architecture simulation + RTL prototyping</li>
</ul>

# 🎖 Honors and Awards
- 2021-2024 Postgraduate Scholarships of USTC
- 2020 Outstanding Graduates of UESTC
- 2018-2020, International Undergraduate Student scholarships of UoB
- 2017 Excellent individual in UESTC
- 2016-2017, 2017-2018 excellent student scholarships of UESTC

# 💬 Invited Talks
- 2025.11, Oral talk to present ICCD 2025 accepted paper FlexIO: A Scalable IO Chiplet Architecture with Flexible Memory Controller Mapping

# 💻 Taped Out Chip Projects

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CPU chiplet and IO chiplet</div><img src='images/prj1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Zhejiang Big Chip
- supporting up to 512 cores and 128 chiplets with sub-100 ns inter-chiplet coherence latency.
- my contributions: architecture exploration, high-level cache design, RTL implementation & verification.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Dadu-Eye</div><img src='images/prj2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Dadu-Eye Stereo Vision Chip
- delivering efficient depth perception with a peak performance of 1 TOPS/W.
- my contributions: algorithm & modeling, chip testing.
</div>
</div>

# 🛠️ Skill
- Programming Skill: Python, C/C++, Shell, Verilog, Chisel
- Tools/Simulators: Vivado, Gem5, Ramulator, MATLAB
- Language: Mandarin, Cantonese (my hometown is Guangdong), English

# 💼 Internships
- 2021 - 2026, Research Assistant at Center for Intelligent Computing Systems, National Key Laboratory of Processors, Institute of Computing Technology, Chinese Academy of Sciences (中国科学院计算技术研究所-处理器全国重点实验室-智能计算机研究中心)
- 2024 - 2026, SoC Designing Engineer at Beijing Institute of Open Source Chip (北京市开源芯片研究院, BOSC)
# 🌍 Visitor Map

<script type='text/javascript' id='mapmyvisitors' src='https://mapmyvisitors.com/map.js?cl=080808&w=250&t=tt&d=wHSzOYLT4svRXt9P8u8ffZ7iQMNh1k5WSMY3rUUEdio&co=ffffff&cmo=3acc3a&cmn=ff5353&ct=808080'></script>
