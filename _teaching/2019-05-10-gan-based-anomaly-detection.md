---
title: "GAN-based Anomaly Detection"
collection: teaching
type: "Master Thesis"
permalink: /teaching/2019-05-10-gan-based-anomaly-detection
student: "Nils Murzyn"
date: 2019-05-10
location: "Karlsruhe, Germany"
tags:
  - master
  - thesis
  - anomaly detection
  - GAN
pdf:
data:
code:
bibtex:
excerpt: "Anomaly detection plays an important role in a wide range of applications. In the field of video surveillance, image-based detection of an anomalous situation should be achieved. The requirements for  ..."
---

Anomaly detection plays an important role in a wide range of applications. In the field of video surveillance, image-based detection of an anomalous situation should be achieved. The requirements for an anomaly detection system are extremely complex, as it is essential to identify temporal and spatial anomalies as well as anomalous appearances.
Driven by the exponential increase of the efficiency of machine learning methods (especially deep learning), they find a multitude of applications in the field of anomaly detection. Currently, particularly generative methods are the subject of research.
In this thesis, anomaly detection was investigated with the help of Generative Adversarial Networks (GANs), which can be assigned to generative methods. GANs consist of two networks, a generator that generates data and a discriminator that distinguishes between generated and real data. The aim is to learn normal movement patterns and normal appearances and thereby detect anomalies. For this purpose, a cross-channel approach according to a domain transfer was used, in which the camera data were transferred into optical flow with the help of a generator and vice versa. The resulting transfer error was used to classify the data with respect to anomalies. Within the scope of this work, different variants for the calculation of an anomaly score were investigated. Furthermore, the influence of a variation of the calculation method of the optical flow was examined. Finally, the effect of an extension of the cross-channel approach and its robustness against scenes with different backgrounds was evaluated.
