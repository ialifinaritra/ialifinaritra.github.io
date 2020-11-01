---
layout: single
title: "Projects"
permalink: /projects/
author_profile: true
classes: wide
header :
    image: "/assets/images/banner.jpg"
---


## [French Text Summarization](https://github.com/ialifinaritra/Text_Summarization)
<img align="left" width="400px" height="400px" style="padding-right:25px" src="/assets/images/summaries.png">

This Module is a Summarizer using Hugging face's Transformers library, which provides general-purpose architectures for NLP, in particual the BERT architecture. This module proposes 3 methods of summarization : Mean summarization, Clustering summarization, Graph Summarization.
The module is based on [Camembert](https://camembert-model.fr/) and [Flaubert](https://arxiv.org/abs/1912.05372).


## [Music Sequence Generation](https://github.com/ialifinaritra/Music_Generation)
<img align="left" width="400px" height="400px" style="padding-right:25px" src="/assets/images/bach.jpg">
The main goal of this project is to train a reccurent neural netwrok in order to learn a language model and then use the model to generate new sequences. The model will be trained to learn the language of music of Johan_Sebastian_Bach. 
For this, the model will learn how J.S Bach's "Cello suite" have been composed and then will be able to generate new music sequences from random notes given to it.


## [Image Object Detection](https://github.com/ialifinaritra/Image_Object_Detection)
<img align="left" width="400px" height="400px" style="padding-right:25px" src="/assets/images/yolov3.jpg">
This is an object detection implementation using yolo V3 and openCV. This latter proposes an simple API to read darknet pretrained models and enables to exploit easily YOLO model. The model is served in a simplified interface built with FLASK.

<br>

## [GDELT Project](https://github.com/ialifinaritra/Gdelt-Project)

<img align="left" width="400px" height="400px" style="padding-right:25px" src="/assets/images/GDELT.jpg">
The goal of this project is to build a resilient database architecture to store large amount of data and allows analysis on GDELT dataset and its data sources. It will allow to see to see the evolution of relations between different countries by studiyng the tone of the mentions in the articles.

The stack used in this project are AWS using EC2 and S3 bucket, Cassandra and SPARK.