---
permalink: /zh/
title: ""
excerpt: ""
author_profile: true
lang: zh
---
<style>
.language-switch {
  text-align: right;
  margin: 0 0 20px;
  font-size: 14px;
}
.language-switch a {
  color: #0066d6;
  text-decoration: none;
}
.language-switch .active {
  font-weight: 700;
  color: #24292f;
}
</style>

<div class="language-switch">
  <a href="{{ '/' | relative_url }}">English</a>
  &nbsp;|&nbsp;
  <span class="active">中文</span>
</div>
{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

正在施工中，请稍后...

# ℹ️ 自我介绍

黄俊培博士毕业于中国科学技术大学微电子学院，师从[韩银和教授](https://scholar.google.com/citations?user=t40cM-4AAAAJ&hl=zh-CN&oi=sra)，并与[王颖教授](https://scholar.google.com/citations?user=5LoFPSQAAAAJ&hl=zh-CN&oi=ao)、[许浩博副研究员](https://ieeexplore.ieee.org/author/37087137171)和[甘一鸣副研究员](https://scholar.google.com/citations?user=d-1MZhIAAAAJ&hl=zh-CN&oi=ao)保持密切的科研合作。博士期间，他作为联合培养博士生，在中国科学院计算技术研究所处理器全国重点实验室智能计算机研究中心（CICS@ICT, CAS）开展科研工作。**在芯片设计方面**，2020年至2022年，我参与了中国科学院战略性先导科技专项（C类）支持的“大度”（Dadu-Eye）深度学习边缘处理器的建模与测试工作；2022年至2025年，深度参与了国家重点研发计划支持的“大芯片”（Big Chip）多芯粒处理器的设计与验证工作；自2025年起，参与了中科院某项目支持的8核 RISC-V 某领域计算芯片的前端集成工作。**在科研项目方面**，博士期间，我积极协助导师申报多项科研项目（如国家重点研发计划项目），包括项目预申报书、正式申报书及答辩汇报材料的撰写与完善；同时参与组织和支持芯片第三方现场测试工作，并负责阶段性报告材料的编写。**在学术研究方面**，我的研究兴趣主要包括多芯粒存储系统体系结构设计，重点关注芯粒系统中的缓存一致性、I/O 芯粒体系结构、可扩展多芯粒存储子系统以及领域专用加速器设计。目前，我已在芯粒系统和人工智能加速器相关领域发表9篇学术论文<a href="https://scholar.google.com/citations?user=R6GxAr0AAAAJ&hl=zh-CN" target="_blank" rel="noopener" style="text-decoration:none;">
  📚
</a>，另有4篇论文正在审稿中，并拥有1项发明专利申请。

<span class="anchor" id="educations"></span>

# 📖 教育背景
- 2016.09 - 2020.07, **电子科技大学（UESTC）**，中国四川成都
  - 电子科学与技术专业，工学学士，GPA：3.93/4.0，专业排名：前10%，获得推免资格
- 2018.09 - 2020.07, **伯明翰大学（UoB）**，英国伯明翰
  - 电子与电气工程专业，工学学士（2+2 联合培养双学位项目），GPA：4.25/4.25，学位等级：一等荣誉学位（First Class）
- 2020.09 - 2026.10, **中国科学技术大学（USTC）**，中国安徽合肥
  - 电子科学与技术专业，工学博士，硕博连读，GPA：3.88/4.3
  - 
<span class="anchor" id="news"></span>

# 🔥 科研新闻
- *2026.08*: &nbsp;🎉🎉 论文《A Scalable I/O-Chiplet Architecture with Learning-Guided Monte Carlo Tree Search for Memory Controller Mapping》（FlexIO@ICCD 的扩展版本）收到 IEEE TCAD 的大修（Major Revision）决定。
- *2026.07*: &nbsp;🎉🎉 论文《HybridIO: Enabling Bandwidth-Aware Memory Access Offloading for Multi-Chiplet Systems with CXL-Based Hybrid Memory》被 MEJ 2026 接收。
- *2026.02*: &nbsp;🎉🎉 论文《SAP: Shared-Aware Prefetching for Reducing Inter-Chiplet Data Access Latency》被 CAL 2026 接收。
- *2025.11*: &nbsp;🎉🎉 赴美国得克萨斯州达拉斯参加 ICCD 2025 国际会议，并对论文 FlexIO 进行口头报告（Oral Presentation）。
- *2025.08*: &nbsp;🎉🎉 论文《FlexIO: A Scalable IO Chiplet Architecture with Flexible Memory Controller Mapping》被 ICCD 2025 接收。

<span class="anchor" id="publications"></span>

# 📝 近期论文发表情况、在投/审论文与专利
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
<h2>📋 Selected Publications</h2>
<article class="paper-card"><div class="paper-title">FlexIO: A Scalable IO Chiplet Architecture with Flexible Memory Controller Mapping</div><div class="paper-authors"><span class="me">Junpei Huang</span>, Haobo Xu, Ying Wang, et al.</div><div class="paper-meta"><span class="paper-badge venue">ICCD 2025</span><span class="paper-detail">43rd IEEE International Conference on Computer Design · pp. 674–681 · Oral Presentation, Dallas, USA</span></div></article>
<article class="paper-card"><div class="paper-title">SAP: Shared-Aware Prefetching for Reducing Inter-Chiplet Data Access Latency</div><div class="paper-authors"><span class="me">Junpei Huang</span>, Haobo Xu, Yiming Gan, et al.</div><div class="paper-meta"><span class="paper-badge venue">IEEE CAL 2026</span><span class="paper-detail">IEEE Computer Architecture Letters · Volume: 25, Issue: 1, Jan.-June 2026</span></div></article>
<article class="paper-card"><div class="paper-title">HybridIO: Enabling Bandwidth-Aware Memory Access Offloading in Multi-Chiplet Systems with CXL-Based Hybrid Memory</div><div class="paper-authors"><span class="me">Junpei Huang</span>, Haobo Xu, Ying Li, et al.</div><div class="paper-meta"><span class="paper-badge venue">MEJ 2026</span><span class="paper-detail">Microelectronics Journal · 107398</span></div></article>
<article class="paper-card"><div class="paper-title">Application-Directed Hybrid Coherence for Wafer-Scale Supercomputing System</div><div class="paper-authors">Meixuan Lu, Haobo Xu, Yiming Gan, <span class="me">Junpei Huang</span>, et al.</div><div class="paper-meta"><span class="paper-badge venue">IEEE CAL 2026</span><span class="paper-detail">IEEE Computer Architecture Letters · Volume: 25, Issue: 2, July-Dec. 2026</span></div></article>
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
<section class="publication-section">
<h2>📋 Patents</h2>
<article class="paper-card">
  <div class="paper-title">
    用于维护芯粒间缓存一致性的硅光网络
  </div>
  <div class="paper-authors">
    胡义康、王梦迪、<span class="me">黄俊培</span>、王颖、王郁杰、韩银和
  </div>
  <div class="paper-meta">
    <span class="paper-badge venue">CN121455899A</span>
    <span class="paper-badge review">发明专利申请</span>
    <span class="paper-detail">
      中国 · 2026年2月3日公开
    </span>
  </div>
</article>
</section>

<span class="anchor" id="research-topics"></span>

# 🔬 研究主题

## 🧩 芯粒系统
<p style="text-align:center; margin:10px 0;">
  <img src="/images/topic1.png" alt="Chiplet Systems"
       style="max-width:92%; height:auto; border-radius:10px;">
</p>
<p>
  <!-- TODO: 写 chiplet 的文字说明 -->
我主要从事多芯粒存储体系结构研究，重点关注 I/O 芯粒、内存控制器映射以及可扩展的片间互连与缓存一致性机制。同时，我也对机器学习驱动的硬件优化与设计空间探索（Design Space Exploration, DSE）感兴趣。
</p>
<ul>
  <li><!-- TODO --> Key directions: heuristic-based memory controller mapping / learning-based memory controller mapping / DDR- and CXL- hybrid memory system and scheduling / inter-chiplet prefetching </li>
  <li><!-- TODO --> Methods: Gem5 + DRAMSim3 + DSNet</li>
</ul>

<hr style="margin:18px 0; opacity:0.2;">

## 🧠 AI加速器
<p style="text-align:center; margin:10px 0;">
  <img src="/images/topic2.png" alt="AI Accelerators"
       style="max-width:92%; height:auto; border-radius:10px;">
</p>
<p>
  <!-- TODO: 写 AI accelerator 的文字说明 -->
我致力于探索高效的人工智能加速器体系结构，包括数据流与存储层次结构的协同设计，以及面向新兴人工智能工作负载的系统级优化。
</p>
<ul>
  <li><!-- TODO --> Key directions: NPU/vision chips, throughput/W, dataflow</li>
  <li><!-- TODO --> Methods: architecture simulation + RTL prototyping</li>
</ul>

<span class="anchor" id="honors-and-awards"></span>

# 🎖 荣誉奖项
- 2021-2024年，中国科学技术大学研究生学业奖学金
- 2020年，电子科技大学优秀毕业生
- 2018-2020年，伯明翰大学国际本科生奖学金
- 2017年，电子科技大学优秀个人
- 2016-2017年、2017-2018年，电子科技大学优秀学生奖学金

<span class="anchor" id="invited-talks"></span>

# 💬 口头汇报
- 2025.11，在 ICCD 2025 国际会议上对录用论文《FlexIO: A Scalable IO Chiplet Architecture with Flexible Memory Controller Mapping》进行口头报告（Oral Presentation）。

<span class="anchor" id="taped-out-chip-projects"></span>

# 💻 芯片流片项目
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CPU chiplet and IO chiplet</div><img src='/images/图片4.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Zhejiang Big Chip
- 支持最多 512 个处理器核心和 128 个芯粒，芯粒间缓存一致性通信延迟低于 100 ns。
- 个人贡献：体系结构设计空间探索、高层级缓存设计、RTL 实现与功能验证。
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Dadu-Eye</div><img src='/images/图片3.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Dadu-Eye Stereo Vision Chip
- 实现高效的深度感知，峰值能效达到 1 TOPS/W。
- 个人贡献：算法设计与建模、芯片测试。
</div>
</div>

<span class="anchor" id="taped-out-chip-projects"></span>

# 🛠️ 技能
- Programming Skill: Python, C/C++, Shell, Verilog, Chisel
- Tools/Simulators: Vivado, Gem5, Ramulator, MATLAB
- Language: Mandarin, Cantonese (my hometown is Guangdong), English

<span class="anchor" id="internships"></span>

# 💼 实习经历
- 2021 - 2026年，中国科学院计算技术研究所处理器全国重点实验室智能计算机研究中心，科研助理
- 2024 - 2026年，北京市开源芯片研究院（BOSC），SoC 设计工程师
# 🌍 访问地图

<script type='text/javascript' id='mapmyvisitors' src='https://mapmyvisitors.com/map.js?cl=080808&w=250&t=tt&d=wHSzOYLT4svRXt9P8u8ffZ7iQMNh1k5WSMY3rUUEdio&co=ffffff&cmo=3acc3a&cmn=ff5353&ct=808080'></script>
