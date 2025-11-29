---
title: "Knowleadge Based Multimodal CoT Reasoning"
date: 2025-05-13

summary: "A multimodal CoT framework enhanced by evidence grounding and self-consistency."

image:
  filename: VRLM.png
  preview_only: true
---

<!--more-->
{{< figure src="VRLM Pipe.png" caption="VRLM Workflow." >}}

This project, conducted at Columbia University under [**Prof. Zoran Kostic**](https://www.aidl.ee.columbia.edu/), develops a visual reasoning framework to improve the **verifiability and consistency** of multimodal VQA. 

{{< figure src="VRLM Cap.png" caption="A sample where vanilla caption fails to provides proper information for agent to reason." >}}

The method combines **evidence-dense captioning**—which fuses multi-view visual cues into a grounded scene description—with **agentic self-consistency** based on rationale-checked majority voting. Evaluated on Commonsense Reasoning benchmark **A-OKVQA**, the framework yields a **+13 pp** accuracy gain over strong CoT baselines, with ablations showing substantial contributions from both evidence grounding and agent consensus. The research project can be found [**here**](Knowleadge Based Multimodal CoT Reasoning.pdf).