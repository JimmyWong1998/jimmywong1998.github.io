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

Junpei Huang received my Ph.D. degree at the School of Microelectronics, University of Science and Technology of China (USTC), supervised by Prof. [Yinhe Han](https://scholar.google.com/citations?user=t40cM-4AAAAJ&hl=zh-CN&oi=sra). He works closely with Prof. [Ying Wang](https://scholar.google.com/citations?user=5LoFPSQAAAAJ&hl=zh-CN&oi=ao), Associate Prof. [Haobo Xu](https://ieeexplore.ieee.org/author/37087137171) and Associate Prof. [Yiming Gan](https://scholar.google.com/citations?user=d-1MZhIAAAAJ&hl=zh-CN&oi=ao). During his Ph.D. studies, he has conducted research at Center for Intelligent Computing Systems, National Key Laboratory of Processors, Institute of Computing Technology, Chinese Academy of Sciences (CICS@ICT, CAS) as a joint PhD student.

He has been deeply involved in the design and testing of the Dadu-Eye deep-learning edge processor, funded by the CAS Strategic Priority Research Program, as well as the design and validation of the “Zhejiang” Big Chip, supported by National Key Research and Development Program of China.

His research interest includes multi-chiplet memory architecture design, with an emphasis on cache coherence, IO chiplets, and scalable memory subsystems. He has published about 9 papers on chiplet designs and AI accelerators
<a href="https://scholar.google.com/citations?user=R6GxAr0AAAAJ&hl=zh-CN" target="_blank" rel="noopener" style="text-decoration:none;">
  📚
</a>
and have 4 papers under review.

# 📖 Educations
- 2016.09 - 2020.07, **University of Electronic Science and Technology of China (UESTC)**, Chengdu, Sichuan, China
  - B.Eng in Electronic and Science Technology, GPA: 3.93/4.0, Ranking: Top 10%
- 2018.09 - 2020.07, **University of Birmingham (UoB)**, Birmingham, United Kingdom
  - B.Eng in Electronic and Electrical Engineering (2+2 Joint Bachelor's Degree Program), GPA: 4.25/4.25, Ranking: First Class
- 2020.09 - 2026 (now), **University of Science and Technology of China (USTC)**, Anhui, Hefei, China
  - PhD Student in Electronic and Science Technology, GPA: 3.88/4.3

# 🔥 News (Related to my first-author publications)
- *2026.03*: &nbsp;🎉 HybridIO: Enabling Bandwidth-Aware Memory Access Offloading for Multi-Chiplet Systems with CXL-Based Hybrid Memory was accepted to MEJ 2026.
- *2026.02*: &nbsp;🎉🎉 SAP: Shared-Aware Prefetching for Reducing Inter-Chiplet Data Access Latency was accepted to CAL 2026.
- *2025.08*: &nbsp;🎉🎉 FlexIO: A Scalable IO Chiplet Architecture with Flexible Memory Controller Mapping was accepted to ICCD 2025.

# 📝 Publications 
<style>
.publication-section{margin:30px 0}
.publication-section h2{margin-bottom:20px}
.paper-card{background:#fff;border:1px solid #d0d7de;border-radius:12px;padding:22px 26px;margin:0 0 22px;box-shadow:0 2px 5px rgba(0,0,0,.035);transition:transform .2s,box-shadow .2s}
.paper-card:hover{transform:translateY(-3px);box-shadow:0 8px 18px rgba(0,0,0,.09)}
.paper-title{font-size:1.18em;font-weight:650;line-height:1.5;color:#0066d6;margin-bottom:10px}
.paper-authors{line-height:1.7;margin-bottom:12px}
.me{background:#fff7d6;padding:2px 5px;border-radius:3px;font-weight:650}
.paper-meta{display:flex;flex-wrap:wrap;align-items:center;gap:8px}
.paper-badge{display:inline-block;padding:5px 13px;border-radius:20px;font-size:.85em;font-weight:650}
.venue{background:#ddf3ff;color:#0066d6}
.revision{background:#fff3c4;color:#986700}
.review{background:#edf0f3;color:#58636e}
.paper-detail{color:#66717d;font-size:.91em;font-style:italic}
@media(max-width:600px){.paper-card{padding:16px}.paper-title{font-size:1.06em}}
</style>
<section class="publication-section">
<h2>📝 Selected Publications</h2>
<article class="paper-card"><div class="paper-title">FlexIO: A Scalable IO Chiplet Architecture with Flexible Memory Controller Mapping</div><div class="paper-authors"><span class="me">Junpei Huang</span>, Haobo Xu, Ying Wang, et al.</div><div class="paper-meta"><span class="paper-badge venue">ICCD 2025</span><span class="paper-detail">43rd IEEE International Conference on Computer Design · pp. 674–681 · Oral Presentation, Dallas, USA</span></div></article>
<article class="paper-card"><div class="paper-title">SAP: Shared-Aware Prefetching for Reducing Inter-Chiplet Data Access Latency</div><div class="paper-authors"><span class="me">Junpei Huang</span>, Haobo Xu, Yiming Gan, et al.</div><div class="paper-meta"><span class="paper-badge venue">IEEE CAL 2026</span><span class="paper-detail">IEEE Computer Architecture Letters</span></div></article>
<article class="paper-card"><div class="paper-title">HybridIO: Enabling Bandwidth-Aware Memory Access Offloading in Multi-Chiplet Systems with CXL-Based Hybrid Memory</div><div class="paper-authors"><span class="me">Junpei Huang</span>, Haobo Xu, Ying Li, et al.</div><div class="paper-meta"><span class="paper-badge venue">MEJ 2026</span><span class="paper-detail">Microelectronics Journal</span></div></article>
<article class="paper-card"><div class="paper-title">Application-Directed Hybrid Coherence for Wafer-Scale Supercomputing System</div><div class="paper-authors">Meixuan Lu, Haobo Xu, Yiming Gan, <span class="me">Junpei Huang</span>, et al.</div><div class="paper-meta"><span class="paper-badge venue">IEEE CAL 2026</span><span class="paper-detail">IEEE Computer Architecture Letters</span></div></article>
<article class="paper-card"><div class="paper-title">Space-Based Computing Chips: Current Status, Trends and Key Technique</div><div class="paper-authors">Xiaotong Wei, Haobo Xu, Chundi Yin, <span class="me">Junpei Huang</span>, et al.</div><div class="paper-meta"><span class="paper-badge venue">JEIT 2025</span><span class="paper-detail">Journal of Electronics & Information Technology · 47(9): 2963–2978</span></div></article>
<article class="paper-card"><div class="paper-title">The Big Chip: Challenge, Model and Architecture</div><div class="paper-authors">Yinhe Han, Haobo Xu, Meixuan Lu, Haoran Wang, <span class="me">Junpei Huang</span>, et al.</div><div class="paper-meta"><span class="paper-badge venue">Fundamental Research 2024</span><span class="paper-detail">4(6): 1431–1441</span></div></article>
<article class="paper-card"><div class="paper-title">The Decomposition and Combination Paradigms of Chiplet-Based Integrated Chips</div><div class="paper-authors">Fuping Li, Ying Wang, Meixuan Lu, Yutong Zhu, Haoran Wang, Zhun Zhao, <span class="me">Junpei Huang</span>, et al.</div><div class="paper-meta"><span class="paper-badge venue">ICS 2024</span><span class="paper-detail">Integrated Circuits and Systems · 1(1): 18–30</span></div></article>
<article class="paper-card"><div class="paper-title">Dadu-SV: Accelerate Stereo Vision Processing on NPU</div><div class="paper-authors">Feng Min, Ying Wang, Haobo Xu, <span class="me">Junpei Huang</span>, et al.</div><div class="paper-meta"><span class="paper-badge venue">IEEE ESL 2022</span><span class="paper-detail">IEEE Embedded Systems Letters · 14(4): 191–194</span></div></article>
<article class="paper-card"><div class="paper-title">Toward Efficient Computing for Robotics: From a Circuit and System View</div><div class="paper-authors">Haobo Xu, Yuxin Yang, Feng Min, <span class="me">Junpei Huang</span>, et al.</div><div class="paper-meta"><span class="paper-badge venue">IEEE TCAS-II 2022</span><span class="paper-detail">69(7): 3051–3056</span></div></article>
</section>
<section class="publication-section">
<h2>📋 Under Review / Revision</h2>
<article class="paper-card"><div class="paper-title">A Scalable I/O-Chiplet Architecture with Learning-Guided Monte Carlo Tree Search for Memory Controller Mapping</div><div class="paper-authors"><span class="me">Junpei Huang</span>, et al.</div><div class="paper-meta"><span class="paper-badge venue">IEEE TCAD 2026</span><span class="paper-badge revision">Major Revision</span></div></article>
<article class="paper-card"><div class="paper-title">REQ: Request Compression and Elastic Allocation for Memory Request Queues in AI Accelerators</div><div class="paper-authors"><span class="me">Junpei Huang</span>, Haobo Xu, Ying Li, et al.</div><div class="paper-meta"><span class="paper-badge venue">ISCAS 2027</span><span class="paper-badge review">Under Review</span></div></article>
<article class="paper-card"><div class="paper-title">YUUMI: A Plug-and-Play Integration Architecture for RISC-V CPU-Vector Cores</div><div class="paper-authors">Xiaotong Wei, Bowen Liu, Yiming Gan, Haobo Xu, <span class="me">Junpei Huang</span>, et al.</div><div class="paper-meta"><span class="paper-badge venue">ISCA 2027</span><span class="paper-badge review">Under Review</span></div></article>
<article class="paper-card"><div class="paper-title">IRV: A Tightly-Coupled Architecture for Out-of-Order RISC-V CPUs and Vector Cores</div><div class="paper-authors">Xiaotong Wei, Yiming Gan, Haobo Xu, <span class="me">Junpei Huang</span>, et al.</div><div class="paper-meta"><span class="paper-badge venue">IEEE ESL 2026</span><span class="paper-badge revision">Major Revision</span></div></article>
</section>


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

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CPU chiplet and IO chiplet</div><img src='images/' alt="sym" width="100%"></div></div>
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
