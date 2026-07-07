---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<div class="section-card">
<span class="anchor" id="biography"></span>
<h1 id="zhipeng-zhang-张智鹏">Zhipeng Zhang (张智鹏)</h1>

<div class="author-info-inline">
  <span>{% include icon.html name="map-pin" %} Beijing, China</span>
  <span>{% include icon.html name="mail" %} <a href="mailto:zhangzhipeng@pku.edu.cn">Email</a></span>
  <span><a href="https://github.com/zhipeng93">{% include icon.html name="github" %} GitHub</a></span>
  <span><a href="https://scholar.google.com/citations?hl=en&user=RNgBUAIAAAAJ">{% include icon.html name="graduation-cap" %} Google Scholar</a></span>
</div>

<p>I am a software engineer at <a href="https://www.alibaba.com/">Alibaba</a>, working on pre-training and post-training infrastructure for LLMs. I am a core contributor to the pre-training infrastructure that powers <a href="https://arxiv.org/abs/2412.15115">Qwen2.5</a>, <a href="https://arxiv.org/abs/2505.09388">Qwen3</a>, and Qwen3.5. My recent work focuses on Agentic RL infrastructure for the Qwen 3.5/3.6 series. Previously, I co-founded <a href="https://github.com/apache/flink-ml">Flink ML</a>, a distributed machine learning framework built on <a href="https://flink.apache.org/">Apache Flink</a>, where I serve as a Flink Committer.</p>

<p>I received my Ph.D. in Computer Science and Technology from <a href="https://www.pku.edu.cn/">Peking University</a> in 2020, advised by <a href="https://cuibinpku.github.io/">Prof. Bin Cui</a>. My doctoral research focused on big data systems and distributed machine learning systems. I earned my B.S. from <a href="https://www.sdu.edu.cn/">Shandong University</a> (<a href="https://www.tsxt.sdu.edu.cn/">Taishan College</a>) in 2015, advised by <a href="https://www.yorku.ca/xhyu/">Prof. Xiaohui Yu</a>.</p>

</div>

<div class="section-card">
<span class="anchor" id="work-experience"></span>
<h1 id="work-experience">{% include icon.html name="briefcase" %} Work Experience</h1>

<div class="paper-box-text">
<ul>
  <li>Staff Engineer, <strong>Alibaba</strong>, Beijing. (07/2020 - Present)</li>
  <li>Research Intern, <strong>Tencent</strong>, Beijing. (11/2018 - 11/2019)</li>
  <li>Visiting Researcher, <strong>ETH Zurich</strong>, Switzerland. (07/2017 - 01/2018)</li>
</ul>
</div>

</div>

<div class="section-card">
<span class="anchor" id="publications"></span>
<h1 id="publications">{% include icon.html name="book" %} Publications</h1>

<div class="paper-box-text">
<ul>
  <li>
    <p><strong>Accelerating Compound LLM Training Workloads with Maestro</strong></p>
    <p><em>Xiulong Yuan, Hongqing Chen, Jiaxuan Peng, Fan Zhou, Zhixiang Ruan, Zekun Wang, Bo Zheng, Rui Men, Haiquan Wang, <strong>Zhipeng Zhang</strong>, Langshi Chen, Man Yuan, Jiaqi Gao, Zhengping Qian, Junyang Lin, Yong Li, Wei Lin, Junhua Wang, Jingren Zhou</em></p>
    <p>arXiv, 2026 (<a href="https://arxiv.org/abs/2605.10501">arXiv</a>)</p>
  </li>
  <li>
    <p><strong>VRouter: Micro-batch Level Load Balance via Inter-EP Routing for MoE Training</strong></p>
    <p><em>Haiquan Wang, <strong>Zhipeng Zhang</strong>, Guanshujie Fu, Youhui Bai, Jiangfei Duan, Yuan Man, Langshi Chen, Hongqing Chen, Siyu Wang, Xiulong Yuan, Yunfei Mao, Si Chang, Linlang Jiang, Yingtao Li, Yan Wang, Yong Li, Wei Lin, Cheng Li</em></p>
    <p>Preprint, 2026</p>
  </li>
  <li>
    <p><strong>AdaHC: Accelerating Multi-Token Prediction with Adaptive Head Chunking with Pipeline Parallelism</strong></p>
    <p><em>Yan Wang, Chang Si, Kaiming Yang, <strong>Zhipeng Zhang</strong>, Weijian Liu, Man Yuan, Mingzhen Li, Yong Li</em></p>
    <p>ICML, 2026</p>
  </li>
  <li>
    <p><strong>TrainMover: An Interruption-Resilient Runtime for ML Training</strong></p>
    <p><em>ChonLam Lao, Jiaqi Gao, Jiamin Cao, <strong>Zhipeng Zhang</strong>, Pengcheng Zhang, Jiangfei Duan, Minlan Yu, Aditya Akella, Zhilong Zheng, Yu Guan, Yichi Xu, Yong Li, Ennan Zhai, Dennis Cai, Zhengping Qian, Jingren Zhou</em></p>
    <p>OSDI, 2026</p>
  </li>
  <li>
    <p><strong>A Few GPUs, A Whole Lotta Scale: Faithful LLM Training Emulation with PrismLLM</strong></p>
    <p><em>Shaoke Xi, ChonLam Lao, Boyi Jia, Jiaqi Gao, <strong>Zhipeng Zhang</strong>, Jiamin Cao, Brian Sutioso, Erci Xu, Minlan Yu, Kui Ren, Yong Li, Zhengping Qian, Ennan Zhai, Jingren Zhou</em></p>
    <p>SOSP, 2026 (<a href="https://arxiv.org/abs/2605.15617">arXiv</a>)</p>
  </li>
  <li>
    <p><strong>Qwen3 Technical Report</strong></p>
    <p><em>Qwen Team</em> (LLM infra contributor)</p>
    <p>arXiv, 2025 (<a href="https://arxiv.org/abs/2505.09388">arXiv</a>)</p>
  </li>
  <li>
    <p><strong>Qwen2.5 Technical Report</strong></p>
    <p><em>Qwen Team</em> (LLM infra contributor)</p>
    <p>arXiv, 2024 (<a href="https://arxiv.org/abs/2412.15115">arXiv</a>)</p>
  </li>
  <li>
    <p><strong>Infinite-LLM: Efficient LLM Service for Long Context with DistAttention and Distributed KVCache</strong></p>
    <p><em>Bin Lin, Chen Zhang, Tao Peng, Hanyu Zhao, Wencong Xiao, Minmin Sun, Anmin Liu, <strong>Zhipeng Zhang</strong>, Lanbo Li, Xiafei Qiu, Shen Li, Zhigang Ji, Tao Xie, Yong Li, Wei Lin</em></p>
    <p>arXiv, 2024 (<a href="https://arxiv.org/abs/2401.02669">arXiv</a>)</p>
  </li>
  <li>
    <p><strong>Model Averaging in Distributed Machine Learning: A Case Study with Apache Spark</strong></p>
    <p><em>Yunyan Guo, <strong>Zhipeng Zhang</strong>, Wentao Wu, Jiawei Jiang, Ce Zhang, Bin Cui, Jianzhong Li</em></p>
    <p>VLDBJ, 2021</p>
  </li>
  <li>
    <p><strong>ColumnSGD: A Column-oriented Framework for Distributed Stochastic Gradient Descent</strong></p>
    <p><em><strong>Zhipeng Zhang</strong>, Wentao Wu, Jiawei Jiang, Lele Yu, Bin Cui, Ce Zhang</em></p>
    <p>ICDE, 2020</p>
  </li>
  <li>
    <p><strong>PSGraph: How Tencent trains large-scale graphs with Spark?</strong></p>
    <p><em>Jiawei Jiang, Pin Xiao, Lele Yu, Xiaosen Li, Jiefeng Cheng, Xupeng Miao, <strong>Zhipeng Zhang</strong>, Bin Cui</em></p>
    <p>ICDE, 2020</p>
  </li>
  <li>
    <p><strong>A Reinforcement Learning-based Method for Join Optimization</strong></p>
    <p><em>Xinyi Zhang, <strong>Zhipeng Zhang</strong>, Bin Cui</em></p>
    <p>NDBC, 2020 (<strong>Best Student Paper</strong>)</p>
  </li>
  <li>
    <p><strong>PS2: Parameter Server on Spark</strong></p>
    <p><em><strong>Zhipeng Zhang</strong>, Bin Cui, Yingxia Shao, Lele Yu, Jiawei Jiang, Xupeng Miao</em></p>
    <p>SIGMOD, 2019</p>
  </li>
  <li>
    <p><strong>MLlib*: Fast Training of GLMs using Spark MLlib</strong></p>
    <p><em><strong>Zhipeng Zhang</strong>, Jiawei Jiang, Wentao Wu, Ce Zhang, Lele Yu, Bin Cui</em></p>
    <p>ICDE, 2019</p>
  </li>
  <li>
    <p><strong>An Experimental Evaluation of SimRank-based Similarity Search Algorithms</strong></p>
    <p><em><strong>Zhipeng Zhang</strong>, Yingxia Shao, Bin Cui, Ce Zhang</em></p>
    <p>VLDB, 2017</p>
  </li>
</ul>
</div>

</div>

<div class="section-card">
<span class="anchor" id="awards"></span>
<h1 id="awards">{% include icon.html name="trophy" %} Awards</h1>
<ul>
  <li><a href="https://sigmod.org/2023-sigmod-systems-award/"><strong>SIGMOD Systems Award 2023</strong></a></li>
  <li><strong>NDBC 2020 Best Student Paper</strong></li>
  <li><strong>President Scholarship of Peking University</strong>, 2017 & 2016</li>
</ul>
</div>

<div class="section-card">
<span class="anchor" id="blogs"></span>
<h1 id="blogs">{% include icon.html name="blog" %} Blogs</h1>
<p>Selected public posts will be listed here.</p>
</div>
