---
layout: project
type: project
published: true
image:  img/ConfCal-2-859x430.png
title: Multivariate Confidence Calibration for Object Detection
date: 2020
labels:
  - Neural Networks
  - Uncertainty Calibration
summary: Unbiased confidence estimates of neural networks are crucial especially for safety-critical applications. Many methods have been developed to calibrate biased confidence estimates. Though there is a variety of methods for classification, the field of object detection has not been addressed yet. Therefore, we present a novel framework to measure and calibrate biased (or miscalibrated) confidence estimates of object detection methods. The main difference to related work in the field of classifier calibration is that we also use additional information of the regression output of an object detector for calibration. Our approach allows, for the first time, to obtain calibrated confidence estimates with respect to image location and box scale. In addition, we propose a new measure to evaluate miscalibration of object detectors. Finally, we show that our developed methods outperform state-of-the-art calibration models for the task of object detection and provides reliable confidence estimates across different locations and scales.

projecturl: https://github.com/EFS-OpenSource/calibration-framework
---
