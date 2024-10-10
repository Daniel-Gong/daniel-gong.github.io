---
title: "Self-attention limits working memory capacity of Transformer-based models"
collection: publications
permalink: /publication/2024-09-14-self-attention-transformer
excerpt: 'NeurIPS 2024 Workshop on Behavioral Machine Learning'
paperurl: 'https://arxiv.org/abs/2409.10715'
---
Recent work on Transformer-based large language models (LLMs) has revealed striking limits in their working memory capacity, similar to what has been found in human behavioral studies. Specifically, these models' performance drops significantly on N-back tasks as N increases. However, there is still a lack of mechanistic interpretability as to why this phenomenon would arise. Inspired by the executive attention theory from behavioral sciences, we hypothesize that the self-attention mechanism within Transformer-based models might be responsible for their working memory capacity limits. To test this hypothesis, we train vanilla decoder-only transformers to perform N-back tasks and find that attention scores gradually aggregate to the N-back positions over training, suggesting that the model masters the task by learning a strategy to pay attention to the relationship between the current position and the N-back position. Critically, we find that the total entropy of the attention score matrix increases as N increases, suggesting that the dispersion of attention scores might be the cause of the capacity limit observed in -back tasks.


Blog mentions: [https://www.aimodels.fyi/papers/arxiv/self-attention-limits-working-memory-capacity-transformer](https://www.aimodels.fyi/papers/arxiv/self-attention-limits-working-memory-capacity-transformer)
