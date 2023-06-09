# SofToss: Learning to throw objects with a soft robot
This repository contains the supplementary material related to the work developed for the work submitted at IEEE Robotics & Automation Magazine (RAM)
## Abstract
In this paper, we present, for the first time, a soft robot control system (SofToss) capable of throwing life-size objects toward target positions. SofToss is an open-loop controller based on deep reinforcement learning that generates, given the target position, an actuation pattern for the tossing task. To deal with the high non-linearity of the dynamics of soft robots, we deployed a neural network to learn the relationship between the actuation pattern and the target landing position, i.e., the direct model of the task. Then, a reinforcement learning method is used to predict the actuation pattern given the goal position. The proposed controller was tested on a modular soft robotic arm, I-Support, by tossing four objects of different shapes and weights in 140-mm squared target boxes. We registered a success rate of almost 65\% of the throws in two actuation modalities (i.e., partial, keeping one module of the soft arm passive, and complete, with both modules active). This performance raises to 85\% if one can choose the number of modules to actuate for each throwing direction. Furthermore, the results show that the proposed learning-based real-time controller achieves performance comparable to an optimization-based non-real-time controller. Our study contributes to the foundations for bringing soft robots into everyday life and industry, by performing more complex, dynamic tasks.
## Keywords
**Reinforcement Learning, Neural Networks, Throwing Task, Soft Robotics**

## Methodology
TO DO

For futher information, please refer to the original [paper](https://www.overleaf.com/project/642be90435d347c327a56442).
