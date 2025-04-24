---
layout: post
title: AI & Deep learning Introduction
date: 2025-04-24 08:25:00 AM
categories: ai
tags: ai
image:
  path: /assets/img/posts/ai_deep_learning_banner.svg
---

## What is AI?
**Artificial Intelligence (AI)** is the simulation of human intelligence by machines, especially computer systems. It enables machines to perform tasks such as learning, reasoning, problem-solving, understanding language, and perceiving the environment.

## Brief History
![AI timeline](/assets/img/posts/ai_timeline.png)

## Deep learning
**Deep Learning** is a subset of Machine Learning that uses Artificial Neural Networks inspired by the human brain. It involves training models with multiple layers (hence "deep") to automatically learn patterns and features from large amounts of data.

## AI model
In AI, a **model** is a mathematical representation or program that learns patterns from data to make predictions or decisions. It is the core component of AI systems, trained using algorithms on input data to perform specific tasks.

## Deep learning types VS Architectures
**Deep Learning Types** describe the way a model learns from data, while **Deep Learning Architectures** define the design or structure of the neural network used to achieve that learning.

In essence, the type defines "how learning happens," and the architecture defines "how the system is built to achieve it".

## Deep learning types

| Type                     | Description                                                                                                                                              |
| ------------------------ |-------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Supervised Learning      | Learning from labeled data where the model is provided <br> with input-output pairs. It is used for tasks like classification and regression.                 |
| Unsupervised Learning    | Learning from unlabeled data by finding patterns, <br> anomalies, or generating data representations.                                                         |
| Semi-Supervised Learning | Combines a small amount of labeled data with <br> a large amount of unlabeled data to improve learning accuracy.                                              |
| Self Supervised Learning | A form of unsupervised learning where the data provides the supervision. <br> It often involves pretext tasks to learn useful representations without labels. |
| Reinforcement Learning   | Involves an agent learning to make decisions <br> by interacting with an environment to maximize a reward signal over time.                                    |

## Deep learning architectures

| Architecture                          | Description                                                                                                                                           | Example                                                                                 |
| ------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------- |
| Convolutional Neural Network (CNN)    | Uses convolutional layers to extract spatial hierarchies of features <br> from images or grid-like data.                                                   | Image classification, object detection, medical imaging, video analysis            |
| Recurrent Neural Networks (RNN)       | Designed to handle sequential data by maintaining <br> a hidden state that captures information from previous time steps.                                  | Language modeling, time series prediction, speech recognition                           |
| Transformers                          | Uses self-attention mechanisms to process entire sequences simultaneously. <br> Highly parallelizable and effective for capturing long-range dependencies. | Large Language Models, translation (e.g., BERT, GPT), summarization, question answering |
| Generative Adversarial Networks (GAN) | Consists of two networks a generator and a discriminator that <br> compete against each other, leading to the generation of realistic synthetic data.      | Image synthesis, style transfer, data augmentation, super-resolution                    |
| Graph Neural Networks (GNN)           | Designed to handle data structured as graphs by aggregating <br> features from neighbors, useful for relational reasoning with graph-structured data.      | Social network analysis, recommendation systems, chemical molecule analysis             |


## NLP & LLM

- **NLP (Natural Language Processing)**:
    NLP is a broader field in AI focused on enabling machines to understand, interpret, and generate human language. It includes tasks like text classification, sentiment analysis, machine translation, and speech recognition.  

- **LLM (Large Language Models)**:
    LLMs are a subset of NLP, specifically massive pre-trained models (e.g., GPT, BERT) designed to process and generate human-like language. They leverage deep learning and are trained on vast amounts of text data to perform multiple NLP tasks with high accuracy.

## Why is difficult to run a model "locally"?

Running AI models locally on your machine can be challenging due to the following reasons:

- **High Computational Requirements**:  
    AI models, especially large ones like LLMs, require significant GPU/TPU resources and memory, which most personal computers lack.
- **Storage Limitations**:  
    Models can be extremely large (e.g., GPT-3 is over 175 billion parameters), requiring terabytes of storage for weights and datasets.
- **Energy Consumption**: 
    Training or running large models locally can consume substantial power, making it inefficient for personal systems.
- **Software Dependencies**:  
    AI models often depend on complex frameworks, libraries, and drivers, which can be difficult to configure and optimize locally.
- **Scalability Issues**:  
    Local machines struggle to scale for tasks requiring distributed computing or parallel processing, often necessary for advanced AI tasks.
