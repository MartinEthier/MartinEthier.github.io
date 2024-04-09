---
title: "Model Predictive Control on highway-env (ECE 780)"
excerpt: "In this project I try using model predicting control (MPC) for planning on the highway-env simulator. Here I defined an MPC formulation that takes into account trajectory predictions for all other cars, and tries to optimize a plan that makes progress towards the goal while avoiding all other agents over the horizon. The issue with this formulation is the non-convexity of the collision check constraint, which makes the optimization very unstable.<br/><img src='/images/projects/highway_env.gif' style='width:512px;'>"
collection: projects
link: https://github.com/MartinEthier/highway-env-mpc
---
