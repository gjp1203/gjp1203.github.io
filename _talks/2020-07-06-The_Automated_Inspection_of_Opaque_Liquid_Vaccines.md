---
title: "The Automated Inspection of Opaque Liquid Vaccines"
collection: talks
type: "Talk"
permalink: 2020-07-06-The_Automated_Inspection_of_Opaque_Liquid_Vaccines
venue: "Digital European Conference on Artificial Intelligence: August 29-September 8 2020"
date: 2020-07-06
location: "Digital ECAI2020"
---

In the pharmaceutical industry the screening of opaque vaccines containing suspensions is currently a manual task carried out by trained human visual inspectors. We show that deep learning can be used to effectively automate this process. A moving contrast is required to distinguish anomalies from other particles, reflections and dust resting on a vial's surface. We train 3D-ConvNets to predict the likelihood of 20-frame video samples containing anomalies. Our unaugmented dataset consists of hand-labelled samples, recorded using vials provided by the HAL Allergy Group, a pharmaceutical company. We trained ten randomly initialized 3D-ConvNets to provide a benchmark, observing mean AUROC scores of 0.94 and 0.93 for positive samples (containing anomalies) and negative (anomaly-free) samples, respectively. Using Frame-Completion Generative Adversarial Networks we: (i) introduce an algorithm for computing saliency maps, which we use to verify that the 3D-ConvNets are indeed identifying anomalies; (ii) propose a novel self-training approach using the saliency maps to determine if multiple networks agree on the location of anomalies. Our self-training approach allows us to augment our data set by labelling 217,888 additional samples. 3D-ConvNets trained with our augmented dataset improve on the results we get when we train only on the unaugmented dataset.

[To watch the presentation click here.](https://screencast-o-matic.com/watch/cYiill5BoF)
