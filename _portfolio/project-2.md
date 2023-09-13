---
title: "Project 2: Predicting Similar Food Taste"
excerpt: ""
collection: portfolio
permalink: /portfolio/project-2
---

Based on a triplet input (anchor, positive and negative) of food pictures (anchor, similar taste and
distinct taste), a neural network was designed and trained to predict similar food tastes.
The image embeddings were generated using a pretrained neural network.

* Transformed, resized and normalized images to generate embeddings using ResNet50
* Designed neural network using ReLu activation functions via the pytorch library
* Split data into training and validation set
* Multiple epochs were used to train neural network

[This Project's GitHub Repository]()
