---
title: "Comma Calibration Challenge"
excerpt: "This is a recruitment challenge organized by comma.ai where the goal is to estimate the offset between the camera pose and ego heading given video input. This is a very small dataset, so pure machine learning solutions are not likely to generalize well. In the end, my solution utilized visual odometry based on feature tracking using OpenCV. I also trained a semantic segmentation model on the Comma10k dataset to filter out dynamic objects before feature extraction, which gave a 35% relative improvement over the original pipeline. Since this is a recruiting challenge, I've been asked by comma.ai to keep the solution code private.<br/><img src='/images/projects/visual_odometry.png' style='width:512px;'>"
collection: projects
link: https://github.com/commaai/calib_challenge
---
