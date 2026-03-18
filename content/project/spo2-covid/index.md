---
title: "Continuous SpO2 Analysis for COVID-19 Detection"
summary: "Implementation of Machine Learning and Deep Learning pipelines to classify COVID-19 patients based on continuous pulse oximetry signals."
tags:
  - research
date: 2022-06-01
image:
  caption: "SpO2 Signal Analysis"
  focal_point: Smart
---

This university project aimed to identify the presence of COVID-19 using continuous SpO2 monitoring, extracting relevant clinical features like the Oxygen Desaturation Index (ODI).

### Technical Overview
* **Data Processing:** Pre-processing of continuous oximetry data to extract 10 distinct temporal and statistical features.
* **Classical Machine Learning:** Developed and compared Support Vector Machine (SVM) and Random Forest classifiers.
* **Deep Learning Approach:** Implemented and trained a 1D Convolutional Neural Network (ResNet architecture) from scratch to process raw signal segments without manual feature extraction, comparing its performance against classical ML methods.