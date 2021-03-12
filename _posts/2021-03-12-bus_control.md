---
layout:     post
title:      Dynamic holding control to avoid bus bunching: A multi-agent deep reinforcement learning framework
author:     Jiawei Wang
tags: 		post RL Transit control
subtitle:  	
category:   research
---

## Authors
Jiawei Wang, Lijun Sun

## Abstract 

Connected and automated vehicles (CAVs) have attracted more and more attention recently. The fast actuation time allows them having the potential to promote the efficiency and safety of the whole transportation system. Due to technical challenges, there will be a proportion of vehicles that can be equipped with automation while other vehicles are without automation. Instead of learning a reliable behavior for ego automated vehicle, we focus on how to improve the outcomes of the total transportation system by allowing each automated vehicle to learn cooperation with each other and regulate human-driven traffic flow. One of state of the art method is using reinforcement learning to learn intelligent decision making policy. However, direct reinforcement learning framework cannot improve the performance of the whole system. In this article, we demonstrate that considering the problem in multi-agent setting with shared policy can help achieve better system performance than non-shared policy in single-agent setting. Furthermore, we find that utilization of attention mechanism on interaction features can capture the interplay between each agent in order to boost cooperation. To the best of our knowledge, while previous automated driving studies mainly focus on enhancing individual's driving performance, this work serves as a starting point for research on system-level multi-agent cooperation performance using graph information sharing. We conduct extensive experiments in car-following and unsignalized intersection settings. The results demonstrate that CAVs controlled by our method can achieve the best performance against several state of the art baselines.

You can find the full paper [here](https://www.sciencedirect.com/science/article/pii/S0968090X20305763).

## Video
[![Watch the video](https://smart-transport.github.io/img/projects/bus_holding01.png)](https://youtu.be/TuScMyhkL9g)
<!-- <iframe width="560" height="315" src="https://youtu.be/TuScMyhkL9g" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe> -->
<!-- <video src="video.mp4" width="320" height="200" controls preload></video> -->