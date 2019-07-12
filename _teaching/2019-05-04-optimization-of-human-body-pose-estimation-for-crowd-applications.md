---
title: "Optimization of Human Body Pose Estimation for Crowd Applications"
collection: teaching
type: "Master Thesis"
permalink: /teaching/2019-05-04-optimization-of-human-body-pose-estimation-for-crowd-applications
student: "Tobias Kalb"
date: 2019-05-04
location: "Karlsruhe, Germany"
tags:
  - master
  - thesis
  - human pose estimation
  - synthetical data
data:
bibtex:
pdf:
code:
excerpt: "Human pose estimation has recently made significant progress with the adoption of deep convolutional neural networks and the many applications have attracted tremendous interest in recent years. However ..."
---

Human pose estimation has recently made significant progress with the adoption of deep convolutional neural networks and the many applications have attracted tremendous interest in recent years.
However, many of these applications require pose estimation for human crowds, which still is a rarely addressed problem.
For this purpose this thesis explores methods to optimize pose estimation for human crowds, focusing on challenges introduced with larger scale crowds, like occlusions, people in close proximity to each other and partial visibility of people.
In order to address these challenges, multiple approaches are evaluated including: the explicit detection of occluded body parts, a data augmentation method to generate occlusions and the use of the synthetic generated datasets JTA (Joint Track Auto).
The first approach to improve the accuracy in crowded scenarios is to generate occlusions at training time using person and object cutouts from the object recognition dataset COCO (Common Objects in Context).
Furthermore, the synthetically generated dataset JTA is evaluated for the use in real-world crowd applications.
In order to overcome the transfer gap of JTA originating from a low pose variety and less dense crowds, an extension dataset is created to ease the use for real-world applications.
Aditionally, the occlusion flags provided with JTA are utilized to train a model, which explicitly distinguishes between occluded and visible body parts in two distinct branches.
Finally, a small novel benchmark dataset crowdPE is introduced to evaluate the proposed methods for large scale human crowds in a surveillance scenario.
