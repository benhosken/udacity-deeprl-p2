[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/43851024-320ba930-9aff-11e8-8493-ee547c6af349.gif "Trained Agent"


# Project 2: Continuous Control Reacher - Submission

### Introduction

This project is Ben Hosken's submission to for the Deep RL Nanodegree project 2. The environment was solved in 140 episodes.

This prohject uses the [Reacher](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#reacher) environment.

In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

The task is episodic, and in order to solve the environment, the agent must get an average score of +30 over 100 consecutive episodes.

![Trained Agent][image1]


### Getting Started

1. Download the environment from one of the links below.  You need only select the environment that matches your operating system:

    - **_Single Agent_**
        - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux.zip)
        - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher.app.zip)
        - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86.zip)
        - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86_64.zip)

2. Place the file in this folder, and unzip (or decompress) the file. 

### Instructions

Follow the instructions in `DDPG_Reacher.ipynb` to get started with training your own agent.

The agent has already been trained and the checkpointed weights have been saved at `checkpoint_actor.pth` and `checkpoint_critic.pth`

If you wish to just run with the pre-trained weights, run steps 1 and 2 but Not 3. Then run step 4 to see the trained agent in action. 

If you wish to train the agent, rung steps 1, 2 and then 3.

