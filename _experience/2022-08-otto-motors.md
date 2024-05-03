---
title: "OTTO Motors"
collection: experience
permalink: /experience/otto-motors
date: 2022-08-01
link: 'https://ottomotors.com/'
---

In the summer before starting grad school I did an internship at OTTO Motors, which is a division of Clearpath Robotics (now owned by Rockwell Automation). OTTO Motors builds autonomous mobile robots (AMRs) for material handling in warehouses. Think of a pallet that can drive itself around warehouses to transport goods. I worked on the perception team, who's job is to process the sensor inputs to estimate the robot's current position as well as the state of its environment. I spent most of my term building a simulation pipeline to automatically generate training data for our perception models. I ended up using Unity to build a system that procedurally generates virtual warehouse environments, and then extracts training images along with their labels to create large training datasets for computer vision models. The labels extracted include bounding boxes, semantic and instance segmentation labels, as well as depth maps. To validate the effectiveness of the dataset, I trained YOLOv7 object detection models to perform forklift detection. Although the models trained stricly on the simulation datasets were useable, the real value came from using the simulation for pre-training. Pre-training a model on the simulation dataset then fine-tuning it on a small real-life dataset resulted in a 20% improvement in test mAP over fine-tuning from the default COCO weights.

[//]: # (stats: 0.36 mAP sim pre-train zero-shot, 0.54 mAP sim fine-tune, 0.45 mAP COCO fine-tune, 20% improvement in mAP from COCO fine-tune to sim fine-tune, 25% improvement in mAP from pre-train zero-shot to COCO fine-tune)
