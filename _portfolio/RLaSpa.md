---
layout: post
title: Reinforcement learning in the latent space 
feature-img: "assets/img/portfolio/machine-learning.png"
img: "assets/img/portfolio/rl.png"
date: 1 February 2019
tags: [reinforcement learning, neural networks, python, machine learning]
---

In general, reinforcement learning algorithms produce task-specific solutions.
This makes learned knowledge unusable when learning new tasks, although there might be strong
similarities between them. 
However, reinforcement learning often requires expensive training, raising the need for such
transfer learning. 

In this work, we propose a technique of guiding a Deep-Q-Network towards producing more general
abstractions of visual input in order to make transfer to unseen tasks easier.
For this purpose, the encoder producing the representation of the visual input is 
not only trained by the Deep-Q-Network performing the task, but also using multiple decoders
resembling the structure of an autoencoder.

Although we incorporate multiple measures to model dynamics in the representation, our results
show that this task is challenging. 
Knowledge from learning one or multiple tasks did not successfully transfer to unseen tasks. 
Furthermore, an analysis of the latent space produced by the encoder network revealed the
encoder's lack of focus on features relevant to solving the agent's objectives.

The code can be found here: <https://github.com/weidler/RLaSpa>