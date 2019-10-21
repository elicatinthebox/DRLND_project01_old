# Udacity Deep Reinforcement Learning Nanodegree: Project 1 - Navigation

This project repository is based on the materials from the Udacity's [Deep Reinforcement Learning Nanodegree](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893) **Navigation (Project 1)**.

## Project Introduction
This project will train an agent to navigate (and collect bananas) in a large, square world.

![Banana-gif](Banana-gif.gif)

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

* 0 - move forward
* 1 - move backward
* 2 - turn left
* 3 - turn right.

The task is episodic, and in order to solve the environment, the agent must get an average score of +13 over 100 consecutive episodes.

## Getting Started
- Configure a Python 3.6 / PyTorch 0.4.0 environment according to the requirements described in the [Udacity repository](https://github.com/udacity/deep-reinforcement-learning#dependencies) and clone the Udacity's repository.
- Download the Unity environment from one of the links below.
* [Linux](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
* [Mac OSX](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
* [Windows (32-bit)](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
* [Windows (64-bit)](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)

## Required packages

* *pandas*
* *numpy*
* *matplotlib*
* *pytorch*
* *unityagents*

To know more about this project please take a look at the `report.md` file included in this repository.
