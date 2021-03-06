---
title: "ESA-IMITATE"
layout: splash
permalink: /
date: 2016-03-23T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/globe2.jpg
excerpt: "Introducing Machine-learning Into Targeted Analysis for Terrestrial Ecosystems"
intro: 
  - excerpt: 'In this [ESA project](https://eo4society.esa.int/projects/imitate/), we will explore whether machine-earning based emulators are capable of not only reproducing European carbon fluxes from the JULES land surface model but going beyond this and providing a means to derive a novel observation-driven dataset of GPP, built on the existing process-level understanding within the model.'
feature_row:
  - image_path: assets/images/forest.jpg
    alt: "placeholder image 1"
    title: "Question 1"
    excerpt: "How well can machine learning methods emulate physical process-based land surface models, focused over Europe?"
  - image_path: assets/images/globe1.jpg
    alt: "placeholder image 2"
    title: "Question 2"
    excerpt: "Can explainable AI techniques provide new insights into process understanding when combining land surface models and Earth Observation data?"
  - image_path: /assets/images/satellite.jpg
    title: "Question 3"
    excerpt: "Are the learnt relationships between the modelled inputs and outputs consistent with those from Earth Observation data?"
---




{% include feature_row id="intro" type="center" %}

{% include feature_row %}


![image](assets/images/top_level.png){: style="float: right"} In order to answer the above questions, we will undertake the following activities:
* We will produce land surface model simulations from JULES over Europe for a range of terrestrial essential climate variables. 
* We will develop, train and evaluate machine learning models against the simulated land surface parameters, providing the capability to successfully emulate the complex physical process-based models.
* These emulators will be used to investigate the complex emergent relationships and feedbacks inherent in such simulations to gain an increased understanding of the underlying Earth System processes.
* We will use these emulators to test whether data from satellite-based essential climate variables (e.g. ESA-CCI) are consistent with the relationships learnt from the land surface models.
* We will produce an Emulated-GPP (gross primary productivity) data product based on EO data, using the relationships learnt from the land surface model.
