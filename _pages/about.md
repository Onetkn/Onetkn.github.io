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

# 👨‍🎓 Biography / 个人简介

I'm currently an undergraduate student majoring in **Intelligent Medical Engineering** at Beijing University of Posts and Telecommunications (BUPT).

Maintaining a top-tier academic performance (**Rank: 1/25**) laid a profound foundation for my analytical thinking and fast-learning capabilities, empowering my subsequent journey in scientific research and various contests. I also took specialized core courses in **Medical Physiology**, **Pattern Recognition and Machine Learning**, **Digital Image Processing**, and other artificial intelligence foundational courses.

In recent years, I have actively begun exploring my research interests. I am extremely fortunate to start my academic endeavor at the **Center for Artificial Intelligence in Medical Imaging (CAIMI)** at BUPT, where I studied **deep metric learning** for extracting brain functional fingerprints from fMRI data and co-authored my **first academic paper**.

Furthermore, I am honored to have gained research internship opportunities at top-tier laboratories, such as the **Tsinghua Laboratory of Brain and Intelligence (THU THBI)**, after achieving outstanding results in the **CLS-CIBR-IDG Joint Summer School**. These experiences have allowed me to delve deeply into interdisciplinary AI research, including robust cross-subject representation learning for EEG-based precision psychiatry and evaluating **foundation models**.

In my view, while Artificial Intelligence has achieved superhuman proficiency in specific tasks (e.g., processing specific biomedical signals), their ability in handling complex, real-world clinical reasoning still falls short. The next frontier lies in generalizing these capabilities to the messy, complex medical world. My wish is to bridge the gap between high-level AI capabilities and real-world clinical applications to truly liberate productivity. Specifically, I am interested in:

- **LLM-based Agents:** Developing agents for complex workflows and environments, stronger reasoning skills and engineering capabilities.
- **Fundamental LLM Capabilities:** Enhancing the core reasoning efficiency and long-context memory of Large Language Models.
- **Medical Foundation Models:** Exploring the deep integration of large language models and fundamental medicine. By applying advanced AI capabilities to clinical practice, I aim to discover more efficient and effective diagnostic and treatment methods, ultimately improving patient care and medical outcomes.

我是北京邮电大学 (BUPT) 人工智能学院**智能医学工程**专业的在读本科生。

我在本科期间保持了优异的学业成绩（**综合 GPA：3.56/4.0**，**保研排名：1/25**），这为我的分析思维与快速学习能力奠定了坚实的基础，并为我后续的科研与竞赛赋能。另外我还深入学习了**医学生理学**、**模式识别与机器学习**、**数字图像处理**等专业核心课程。

近年来，我逐渐开始探索感兴趣的研究方向。我有幸在**北邮智能医学中心实验室 (CAIMI)** 开启了我的科研之旅，研究基于**深度度量学习**的 fMRI 大脑功能指纹提取，并且合作完成了**第一篇学术论文**。

此外，我非常荣幸能通过在 **CLS-CIBR-IDG 暑期培训班**取得优异成绩后进入**清华大学脑与智能实验室 (THBI)** 等顶尖实验室实习。这些经历让我得以深入探索人工智能交叉领域，包括脑电 (EEG) 精准精神病学的跨域表示学习以及**大模型基准测试**。

在我的认知中，尽管人工智能在处理特定生物医学信号等任务上已超越人类表现，但其在处理复杂临床推理任务的能力仍显不足。未来的关键在于将这些能力泛化至复杂多变的真实医疗世界中。我的愿望是将高水平的 AI 技术与临床应用相结合以真正解放生产力。具体包括：

- **大模型智能体:** 构建能适应复杂工作流程与环境的智能体，更强的推理研究与工程能力。
- **大模型基础能力:** 提升 LLM 的核心推理效率与长上下文记忆能力。
- **医学大模型:** 探索大模型技术与基础医学的深度结合。通过将大模型的能力应用于临床实践，我希望寻找到更高效、更有效的诊疗与干预方式，切实改善临床医疗效果。

<br>

<span class='anchor' id='-news'></span>
# 🔥 News / 最新动态

- **[2025.07]** Participated in the **Tsinghua-PKU CLS-CIBR-IDG Joint Summer School** on Neuroscience and Cognitive Science (**Best Team Award**) and joined the **Tsinghua Laboratory of Brain and Intelligence (THBI)** as a research intern. A manuscript is currently under review for ***ICML 2026***. / 参加**清华-北大神经与认知科学暑期班**获**最佳团队**，并进入**清华大学脑与智能实验室**实习，一篇 ***ICML*** 在投 [[arXiv]](https://arxiv.org/abs/2602.19138)。
- **[2025.03]** Won the **National Third Prize** in the Global Campus AI Algorithm Competition (Application Track: Unmanned Car). / 获得全球校园人工智能算法大赛应用赛（无人小车）**国家三等奖**。
- **[2024.09]** Joined the **Center for Artificial Intelligence in Medical Imaging (CAIMI)** at BUPT as a research intern, which culminated in my **first academic paper** publication. / 进入**北邮智能医学中心**进行科研实习，并成功发表了我的**第一篇学术论文** [[Paper]](https://direct.mit.edu/imag/article/doi/10.1162/IMAG.a.1112/134780)。
- **[2024.07]** Participated in the **6th IEEE EMBS International Summer School of Neural Engineering**, taking my first steps to explore the intersection of neural engineering and machine learning during my freshman year. / 参加**第 6 届 IEEE EMBS 国际神经工程暑期学校**，在大一期间初步学习了神经工程与机器学习的结合方式。

<br>

<span class='anchor' id='-experience'></span>
# 🔬 Research Experience / 科研经历

- **Tsinghua Laboratory of Brain and Intelligence (THBI, THU)**
  <br> *Research Intern | Jul 2025 - Feb 2026*
  <br> Participated in the development of the **CRCC model** for EEG-based precision psychiatry. Assisted in building a **contrastive learning and adversarial optimization framework** to mitigate cross-site and cross-subject biases. Took charge of executing core benchmark testing, conducting comprehensive comparative experiments against foundational models like **EEGPT** on large-scale multi-center MDD cohorts, and profiling **zero-shot** generalization performance.
  <br> *<small>清华大学脑与智能实验室 (THU THBI) | 科研实习；参与用于脑电(EEG)精准精神病学诊断的 **CRCC 模型**开发，协助构建消除跨域偏差的**对比学习与对抗优化框架**。负责在多中心抑郁症(MDD)大队列上执行核心基准测试、与 **EEGPT** 等前沿模型对比实验及**零样本(zero-shot)**泛化性能剖析。</small>*

- **Center for Artificial Intelligence in Medical Imaging (CAIMI, BUPT)**
  <br> *Research Intern | Sep 2024 - Aug 2025*
  <br> Co-developed the **Meltric-BolT model** integrating **deep metric learning** and **Transformer** architectures to extract individual brain functional fingerprints from longitudinal fMRI data. Handled core model training and hyperparameter optimization, and conducted comprehensive performance comparisons and benchmarking against state-of-the-art deep learning baselines utilizing large-scale developmental cohort data.
  <br> *<small>北邮智能医学中心实验室 (CAIMI, BUPT) | 科研实习；参与开发基于**深度度量学习**与 **Transformer** 架构的大脑功能指纹提取模型 **Meltric-BolT**。负责核心模型训练与超参数优化，并在大规模发育队列数据上主导完成与现有前沿深度学习基线模型的综合性能对比与基准测试。</small>*

<br>

<span class='anchor' id='-honors-and-awards'></span>
# 🎖 Honors and Awards / 荣誉奖项

**Honors / 荣誉**
- **First-class Academic Scholarship**, **Merit Student**, and **Active Participant in Arts & Sports**, BUPT <br> *<small>北京邮电大学**校一等学业奖学金**、**校级三好学生**、**校级文体积极分子**</small>* `2023`

<br>
**Competitions / 学科竞赛**
- **Provincial First Prize & National Third Prize**, Global Campus AI Algorithm Competition (Application Track: Brain-controlled Unmanned Car) <br> *<small>全球校园人工智能算法大赛应用赛（脑控无人车） **省一等奖 | 国家三等奖**</small>* `2025`
- **Provincial Second Prize & National Third Prize**, Global Campus AI Algorithm Competition (Application Track: Unmanned Car) <br> *<small>全球校园人工智能算法大赛应用赛（无人小车） **省二等奖 | 国家三等奖**</small>* `2024`
- **National Second Prize**, National English Competition for College Students <br> *<small>全国大学生英语竞赛 **国家二等奖**</small>* `2023`

<br>
**Projects / 项目经历**
- **Member**, National-level Innovation Training Program <br> *<small>**国家级大学生创新创业训练计划（大创）** 核心成员</small>* `2024`

<br>

<span class='anchor' id='-educations'></span>
# 📖 Educations / 教育背景

- **Beijing University of Posts and Telecommunications (BUPT)** | *Intelligent Medical Engineering* | Sep 2023 - Jun 2027 
  <br> **GPA:** **3.56 / 4.0** (86.05/100) | **Comprehensive Evaluation: 1/25** (2023-2025), 2/25 (2025-2026) | **Post-grad Recommendation Rank: 1/25** <br> **Awards:** **First-class Academic Scholarship** (BUPT), **Merit Student** (BUPT) 
  <br> *<small>北京邮电大学 | 人工智能学院 智能医学工程专业 | **GPA 3.56/4.0**, **保研均分加权排名 1/25**，荣获**校一等学业奖学金** </small>*
