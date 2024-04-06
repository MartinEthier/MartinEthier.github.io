---
title: "End-to-End Planning on Comma2k19"
excerpt: "In this project I was exploring training deep learning models for end-to-end planning through behavior cloning. I worked with the comma2k19 dataset, which contains video logs of 33 hours of driving, as well as accurate GPS measurements of the car, which can be converted into driving labels. I explored a lot of dataset preprocessing techniques in this project, namely looking at cleaning and selecting the data to train on. The main architecture I settled on is a CNN to encode individual frames, and an RNN variant to process the features from multiple frames. I also explored different prediction heads, such as simple regression, discretized classification, and mixture density networks.<br/><img src='/images/projects/e2e_demo.gif' style='width:512px;'>"
collection: projects
link: https://github.com/MartinEthier/end-to-end-driving
---
