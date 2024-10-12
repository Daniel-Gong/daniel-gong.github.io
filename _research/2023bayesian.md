---
title: "Bayesian Telephone: Memory Consolidation and Recall as Generative Processes"
collection: research
type: "PhD Student"
permalink: /research/2023-bayesian
venue: "Yale University"
date: 2023-12-05
location: "New Haven, CT, United States"
---
The hippocampus serves a key role in memory acquisition and consolidation, yet it is unknown whether the hippocampus stores raw sensory inputs or merely generative reconstructions of those inputs. In this paper we examined these competing hypotheses of memory representation in the hippocampus. To do so we modeled the hippocampus as a modern Hopfield network and the entorhinal cortex as a variational autoencoder (VAE). We used Mitsuba 3 to generate a Cornell box dataset. In our first model, we passed these scenes directly into our Hopfield network and trained our VAE on the Hopfield network's output when prompted by stimulus. In the second, the model first probabilistically inferred latent parameters for the observations and generated reconstructed observations which were then passed into the Hopfield network to aid in the training of our VAE. We tested the capacity of our models for generative recall of these scenes and found reliable minimization of reconstruction error during recall in both models. We concluded that either representation scheme or a combination of the two might be at work in the human brain. Future studies should explore implementing features such as forgetting and recall vulnerability in our base model and comparing model performance to human performance on recall tasks.

Github page: [Bayesian Telephone: Memory Consolidation and Recall as Generative Processes](https://github.com/Daniel-Gong/final_project/tree/main)
