---
title: "Sim-to-Real Domain Adaptation for Lane Detection and Classification in Autonomous Driving"
collection: publications
permalink: /publication/2022-06-04-sim-to-real-domain-adaptation
date: 2022-06-04
venue: 'IEEE Intelligent Vehicles Symposium (IV)'
link: 'https://arxiv.org/abs/2202.07133'
github: 'https://github.com/anita-hu/sim2real-lane-detection'
citation: 'Hu, C., Hudson, S., Ethier, M., Al-Sharman, M., Rayside, D., & Melek, W. (2022, June). Sim-to-real domain adaptation for lane detection and classification in autonomous driving. In 2022 IEEE Intelligent Vehicles Symposium (IV) (pp. 457-463). IEEE.'
abstract: 'While supervised detection and classification frameworks in autonomous driving require large labelled datasets to converge, Unsupervised Domain Adaptation (UDA) approaches, facilitated by synthetic data generated from photoreal simulated environments, are considered low-cost and less time-consuming solutions. In this paper, we propose UDA schemes using adversarial discriminative and generative methods for lane detection and classification applications in autonomous driving. We also present Simulanes dataset generator to create a synthetic dataset that is naturalistic utilizing CARLA’s vast traffic scenarios and weather conditions. The proposed UDA frameworks take the synthesized dataset with labels as the source domain, whereas the target domain is the unlabelled real-world data. Using adversarial generative and feature discriminators, the learnt models are tuned to predict the lane location and class in the target domain. The proposed techniques are evaluated using both real-world and our synthetic datasets. The results manifest that the proposed methods have shown superiority over other baseline schemes in terms of detection and classification accuracy and consistency. The ablation study reveals that the size of the simulation dataset plays important roles in the classification performance of the proposed methods. Our UDA frameworks are available at https://github.com/anita-hu/sim2real-lane-detection and our dataset generator is released at https://github.com/anita-hu/simulanes.'
---
