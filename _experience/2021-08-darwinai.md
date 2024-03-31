---
title: "DarwinAI"
collection: experience
permalink: /experience/darwin-ai
date: 2021-08-01
link: 'https://www.linkedin.com/company/darwinai/?originalSubdomain=ca'
---

My 7th undergraduate internship was spent at DarwinAI, a company specializing in using deep learning for visual quality inspection. DarwinAI was acquired by Apple in March 2024, likely to utilize their visual quality inspection technology for their own assembly lines. During my internship, I worked on a research project where my goal was to segment weld defects in X-Ray images using deep learning. I trained a U-Net to perform semantic segmentation of the weld defects on an X-Ray image dataset containing a total of 10 ultra high-resolution images. I developed novel methods to extract training data from those 10 images and experimented with training schemes to achieve a final test IoU of 50%. While I worked on the research project, I also lead the research and proof-of-concept implementation of an MLOps-based model training and deployment pipeline. The design was based on [this MLOps pipeline](https://cloud.google.com/architecture/mlops-continuous-delivery-and-automation-pipelines-in-machine-learning) and used PyTorch, Kubeflow, MLflow, and DVC.
