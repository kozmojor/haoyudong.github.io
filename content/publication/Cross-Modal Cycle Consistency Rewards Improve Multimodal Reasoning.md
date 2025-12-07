---
title: "R-C²: Cross-Modal Cycle Consistency Rewards Improve Multimodal Reasoning"
summary: "Zirui Zhang, **Haoyu Dong**, Kexin Pei, Chengzhi Mao (Under Review)"
authors:
  - Zirui Zhang
  - Haoyu Dong
  - Kexin Pei
  - Chengzhi Mao
date: 2025-11-14
featured: true
links:
  - icon: file
    icon_pack: fas
    name: Public Preprint
    url: https://r-c2-cmlab.github.io/Cross-Modal-Cycle-Consistency-Rewards/static/papers/CVXX2026_Cycle_Consist_arxiv.pdf
  - icon: tv
    icon_pack: fas
    name: Project Page
    url: https://r-c2-cmlab.github.io/Cross-Modal-Cycle-Consistency-Rewards/

card_links:
  - name: Paper
    url: "https://r-c2-cmlab.github.io/Cross-Modal-Cycle-Consistency-Rewards/static/papers/CVXX2026_Cycle_Consist_arxiv.pdf"
  - name: Project
    url: "https://r-c2-cmlab.github.io/Cross-Modal-Cycle-Consistency-Rewards/"
---

<!--more-->
{{< figure src="fig1_modality_gap.png" caption="Modality Gap Example." >}}

This project is part of my ongoing research in **Multimodal Large Language Model (MLLM) Post-training**, jointly with [**Prof. Chengzhi Mao**](https://chengzhi-mao.github.io/) (Rutgers) and collaborators.  
Our work introduces **Cross-Modal Cycle-Consistency Rewards (R-C²)** — a label-free reinforcement learning framework that converts **image–text conflicts** inside MLLMs into dense, self-generated rewards. This allows a model to improve its visual–textual reasoning ability **without human annotations**.

{{< figure src="c3r_cycle_overview.png" caption="Overview of the R-C² pipeline." >}}

In summary, R-C² introduces a simple yet effective self-rewarding paradigm that turns modality contradictions into dense RL signals, enabling consistent improvements across diverse multimodal reasoning tasks.

R-C² improves a broad range of benchmarks including **ScienceQA, ChartQA, DocVQA, InfoVQA, MathVista**, and **A-OKVQA**, achieving up to **+7.6 accuracy improvement** under the same model backbone.  
The paper is currently **under review at one of the CCF-A conferences**.

📕📕📕The **preprint version** of the paper can be found here:  
📚📚📚 [Preprint PDF](https://r-c2-cmlab.github.io/Cross-Modal-Cycle-Consistency-Rewards/static/papers/CVXX2026_Cycle_Consist_arxiv.pdf)

⭐⭐⭐For a more intuitive understanding, you can browse the **interactive project page** I designed for this work:  
🌠🌠🌠 [Project Website](https://r-c2-cmlab.github.io/Cross-Modal-Cycle-Consistency-Rewards/) 