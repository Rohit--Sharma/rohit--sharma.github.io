---
layout: page
title: Projects
subtitle: Office: 4235, Computer Sciences & Statistics, UW-Madison
---

## Research Projects

### Beyond Fine-tuning: Few-Sample Sentence Embedding Transfer

#### Abstract

Fine-tuning (FT) pre-trained sentence embedding models on small datasets has been shown to have limitations.
In this paper we show that concatenating the embeddings from the pretrained model with those from a simple sentence embedding model trained only on the target data, can improve over the performance of FT for few-sample tasks.
To this end, a linear classifier is trained on the combined embeddings, either by freezing the embedding model weights or training the classifier and embedding models end-to-end.
We perform evaluation on seven small datasets from NLP tasks and show that our approach with end-to-end training outperforms FT with negligible computational overhead.
Further, we also showthat sophisticated combination techniques like CCA and KCCA do not work as well in practice as concatenation.
We provide theoretical analysis to explain this empirical observation.

**Paper:** Coming soon (*To appear in AACL-IJCNLP 2020*)

## Graduate Course Projects

### CS 744: Big Data Systems

#### FastTran: Improving Performance of Fine-tuning in Transformer Models

In recent years, Transformer models have been widely used for various Natural Language Processing tasks and have achieved state-of-the-art accuracy.
However, these models are computationally expensive and require a lot of time even for fine-tuning.
In this work, we use various profiling techniques to understand the workload patterns of Transformer models.
We introduce \system, a system that uses a caching mechanism to reduce the fine-tuning time for Transformer models.
We also propose some future research directions that could further increase performance and reduce times for this workload.

**Project Report:** [Big Data Course Project](./CS744_Project_Report.pdf)

### CS 766: Computer Vision

#### Lane Detection in Adverse Visibility Conditions

Given the fact that we are headed towards autonomous driving vehicles, lane detection becomes one of the keyaspects for it.
Although, there has been some work in the domain of Lane Detection, real time implementation of robust lane detection algorithms is still missing for adverse visibility conditions.
In fact, Escanilla et al at UW-Madison have done some novel work in the domain of lane detection last year.
Over the years, several works on detection of lanes in adverse conditions from image scenes have been proposed.
We have researched over the task of lane detection in conditions such of glare, provide assistance in autonomous driving vehicles.

**Website:** [Project Webpage](https://rohit--sharma.github.io/UWMad-CS766_Project/)

### CS 839: Learning Based Methods in Computer Vision

#### Using Multimodal Video and Language Representation for Video Question Answering

Video Question Answering is the task of answering questions given videos and natural language (subtitles or audio) as the context.
In this task, the challenge is to incorporate information from both videos and language in a way that makes it easier for spatio-temporal reasoning which is important for video question answering.
In this work, we explore a technique of multimodal representation learning to jointly learn representations using various video and language based features such as action recognition and BERT in the realm of video question answering.

**Project Report:** [Computer Vision Course Project](./CS838_Project_Report.pdf)

### CS 839: Data Science - Algorithms and Principles

The goal of this project is to get our hands "dirty" as a budding data scientist (and to practice certain materials taught in the class). The project helped us gain a much better appreciation for working with "data in the wild", a better understanding of what it means to work as a data scientist, a deeper understanding of the class materials, a deeper understanding of how to use and debug machine learning models, a chance to work with popular data science tools in Python, and a glimpse into some research efforts in data science.

Specifically, in this project, we collected data, "wrangled" the data by extracting/cleaning/matching/integrating the data into a single unified data set, then analyzed that data set to infer insights.

**Website:** [Project Webpage](https://rohit--sharma.github.io/CS839_DataScience/)
