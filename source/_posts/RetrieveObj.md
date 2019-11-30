---
title: Retrieving an Object from Dense Clutter
date: 2019-8-26 20:36:49
categories: Projects
mathjax: true
cover_image: images/Title_Card_1.jpg
---

# Introduction

This is the first research project I was involved in. It is a system development project investigating the object search problem which is essential for many robotics applications like warehouse retrieval and household chores. The novelty of this project lies in inferring the occluded volume based on state-of-art shape completion. 

# My Contribution

I conducted experiments and designed corner cases to demonstrate how shape completion and volumetric memory promote the performance based on my understanding of algorithmic details. The experiment results were eventually published in an [ISRR paper](https://arxiv.org/abs/1907.08770). 

Through this experience, I was exposed to many fundamental robotics algorithms, which helped me build a systematical understanding of Robotics. Take manipulation as an example: Since we are using a robot arm with 7 degrees of freedom, there is no unique geometrical solution to the inverse kinematics, leading to the use of gradient descend. Besides, moving the robot arm to the desired pose is not as simple as just setting all joint angles. Motion planning in the configuration space and checking collision along the trajectory are necessary for an efficient and safe motion. 

# Demo Video

<iframe width="560" height="315" src="https://www.youtube.com/embed/BXgkv2nFvM4" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# Publication

[Inferring Occluded Geometry Improves Performance when Retrieving an Object from Dense Clutter](https://arxiv.org/abs/1907.08770)
Andrew Price, Linyi Jin, and Dmitry Berenson
International Symposium on Robotics Research (ISRR)