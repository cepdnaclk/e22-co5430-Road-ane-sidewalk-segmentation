---
layout: home
permalink: index.html

# Please update this with your repository name and title
repository-name: e22-co5430-Road-ane-sidewalk-segmentation
title: Autonomous Driving Context Awareness
---

[comment]: # "This is the standard layout for the project, but you can clean this and use your own template"

# Autonomous Driving Context Awareness: Semantic Segmentation

---

<!-- 
This is a sample image, to show how to add images to your page. To learn more options, please refer [this](https://projects.ce.pdn.ac.lk/docs/faq/how-to-add-an-image/)

![Sample Image](./images/sample.png)
 -->

## Team
-  e22303, R.B.R.M.D. RAJAPAKSHA , [email](mailto:e22303@eng.pdn.ac.lk)
-  e22125, D.D.S.K.GUNAWARDHANA, [email](mailto:e22125@eng.pdn.ac.lk)


## Table of Contents
1. [Introduction](#introduction)
2. [Methodology & Architecture](#methodology--architecture)
3. [Links](#links)

---

## Introduction

This project addresses the critical real-world challenge of autonomous driving context awareness. By developing an advanced semantic segmentation pipeline, the system categorizes environmental features in real-time, focusing specifically on roads, lanes, and sidewalks. Utilizing the CARLA dataset, the solution implements optimized deep learning architectures to accurately interpret complex driving scenarios, ultimately contributing to safer and more reliable autonomous navigation systems.

## Methodology & Architecture

This section details the machine learning pipeline, including:
*   **Loss Optimization:** Integration of CrossEntropy and Dice loss functions to handle imbalanced classes.
*   **Data Augmentation:** Implementation of environmental shifts and scaling to improve model generalization.
*   **Mask Decoding:** Utilization of an O(1) GPU lookup table for highly efficient data processing.

## Links

- [Project Repository](https://github.com/cepdnaclk/{{ page.repository-name }}){:target="_blank"}
- [Project Page](https://cepdnaclk.github.io/{{ page.repository-name}}){:target="_blank"}
- [Department of Computer Engineering](http://www.ce.pdn.ac.lk/)
- [University of Peradeniya](https://eng.pdn.ac.lk/)


[//]: # (Please refer this to learn more about Markdown syntax)
[//]: # (https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
