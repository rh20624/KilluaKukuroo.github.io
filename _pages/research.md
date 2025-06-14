---
title: "Research"
classes: wide
permalink: /research/
author_profile: true
---

## Overview
My research interests broadly lie in Human-centric Cyber-Physical Systems, Data Science, Generative AI, IoT, and Mobile and Ubiquitous Computing for smart cities. My work involves various techniques, such as large language models (LLMs), large sensor models (LSMs), efficient machine learning, unsupervised machine learning, cross-domain data fusion, and large-scale system optimization & deployment. I have been investigating platforms across more than 300 cities on 2 continents with 2 billion E-commerce orders, 300 thousand vehicles, 500 thousand mobile devices, and 500 million residents involved. 

### Generative AI and LLMs for Smart Cities
Generative AI and LLMs have transformed many research and application directions. In smart cities, Generative AI has the potential to address some long-standing challenges, such as optimizing resource allocation and enhancing urban planning. One of my works specifically focuses on developing generative AI models to generate urban infrastructure data. By harnessing the unique properties of spatio-temporal and sensory data, I have developed a model called DualSTGAN, which generates urban road maps from multi-modal sensor data. The results of this research have been published in [Ubicomp'24](https://dl.acm.org/doi/abs/10.1145/3659596). Recently, our work about generating spatio-temporal human mobility data with diffusion models has been accepted in [SDM'25](https://epubs.siam.org/doi/10.1137/1.9781611978520.58). 

We have also been investigating LLMs to improve real-world systems in smart cities. For example, we designed an LLM framework for spatial language processing and spatial area processing, and the results have been published in [KDD'25](https://arxiv.org/abs/2411.13584) and **ACL'25**. Also, we have improved the anomaly detection in logistics delivery with local LLMs, this work has also been accepted by KDD'25. To enable more accurate recognition of human activity, we transfer the knowledge from LLMs and successfully deploy LLMs on smartphones for on-device inference (**LLM4HAR**, **KDD'25**). 

<img src="/assets/images/GenAI.jpg" alt="恐龙" style="display: block; margin: 0 auto; width: 75%;" />

### Foundation Model for Wearable AI and Human Activity Sensing
Human activity sensing, or human behavior sensing, plays a crucial role in multiple applications, such as healthcare monitoring, fitness tracking, and smart home. The widespread adoption of mobile and wearable devices has opened up new opportunities for low-cost human activity sensing. However, two persistent challenges—*domain shift* and *limited training data*—have hindered the large-scale deployment of activity sensing models. My research focuses on developing foundational models for generalizable activity sensing by creating novel sensor augmentation techniques and sensor pretraining paradigms. The findings from this work have been published in [Ubicomp'24](https://dl.acm.org/doi/10.1145/3659597). More recently, we push the Wearable AI further by training efficient LLMs and deploy them on smartphones for on-device human activity sensing (**LLM4HAR**, **KDD'25**). 

<img src="/assets/images/foundation_model.jpg" alt="恐龙" style="display: block; margin: 0 auto; width: 75%;" />

### AI-enhanced Low-cost & Nationwide Mobile Sensing
In recent years, rapid economic growth and human mobility have led to significant changes in urban environments, especially in developing countries. For example, the frequent establishment of new points of interest (POIs) and the construction of new buildings. Failing to capture these updates promptly brings negative impacts to smart cities, such as inaccurate map navigation and increased carbon emissions. By leveraging the unique capabilities of mobile devices (e.g., smartphones and smartwatches) carried by citizens, we conceptualize individuals as dynamic sensors for the city. I have designed an innovative framework for urban sensing, utilizing TB-level multi-modal data (e.g., GPS and WiFi), from urban delivery systems such as JD Logistics and Amazon. With this framework, I have identified the locations of shipping addresses and POIs across 366 cities. The findings have been published in [TKDE'24](https://ieeexplore.ieee.org/document/10552380), [Ubicomp'24](https://dl.acm.org/doi/abs/10.1145/3659596), [CIKM'23](https://dl.acm.org/doi/10.1145/3583780.3614724), [CIKM'23](https://dl.acm.org/doi/10.1145/3583780.3614658), and [SIGSPATIAL'22](https://dl.acm.org/doi/10.1145/3557915.3560944). 

<img src="/assets/images/framework.png" alt="恐龙" style="display: block; margin: 0 auto; width: 80%;" />
