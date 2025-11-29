---
title: "RoPerformer: Rotary Positional Embedding Mechanism on Sparse Attention Architecture"
date: 2024-12-10

summary: "Analyzing rotary positional embeddings on sparse-attention architectures and evaluating their impact."

image:
  filename: RoPerformer.jpg
  preview_only: true
---

<!--more-->
While transformers handle many tasks remarkably well, their performance heavily depends on how positional information is represented. However, learning long-range and stable positional representations remains difficult—especially when we aim to make attention both faster and more scalable.

{{< figure src="Performer.png" caption="Vanilla Attention Mechanism." >}}

This project is advised by **Prof.Krzysztof Choromanski** as final project for course **IEOR6617 Machine Learning and High-Dimensional Data** in Columbia, which focuses on the **rotary positional embedding mechanism** on both classical **Transformer** and **Sparse-Attention based Transformer(Performer)**. We conducted thorough experiments involving both models and several **SOTA** positional embedding mechanisms on **CIFAR100** dataset and gave detailed analysis in [**final report**](exploring-transformer-models.pdf) on our results.