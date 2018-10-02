
# Udacity's Deep Reinforcement Learning Nanodegree Project

## "Project 1 - Navigation"

This repository contains code related to "Project 1 - Navigation" from Udacity's Deep Reinforcement Learning Nanodegree program.

### Project Instructions

This repo will train a DeepRL agent to solve a
[Unity Environment]. (<https://github.com/Unity-Technologies/ml-agents).>

To solve the environment, the DeepRL agent must get an average score of +13 over 100 consecutive episodes.

### The Unity Environment

For this project, we train an agent to navigate (and collect bananas!) in a large,  [square world](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#banana-collector).

![Banana Env - gif](./img/banana.gif "Banana Env")

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

0 - move forward.
1 - move backward.
2 - turn left.
3 - turn right.

The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.

### Setup

#### Step 1: Clone the DRLND Repository

If you haven't already, please follow the instructions in the [DRLND GitHub repository](https://github.com/udacity/deep-reinforcement-learning#dependencies) to set up your Python environment. By following these instructions, you will install PyTorch, the ML-Agents toolkit, and a few more Python packages required to complete the project.

#### Step 2: Download the Unity Environment

You will not need to install Unity - this is because we have already built the environment for you, and you can download it from one of the links below. You need only select the environment that matches your operating system:

Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)

#### Step 3:
If you want to visualize the graph of pytorch model. You have to install this [lib](https://github.com/szagoruyko/pytorchviz)

#### Instructions

**TODO**

--------------
Your GitHub Submission
As described in the rubric, your GitHub submission should contain:

a README that describes how someone not familiar with this project should use your repository. The README should be designed for a general audience that may not be familiar with the Nanodegree program; you should describe the environment that you solved, along with how to install the requirements before running the code in your repository.
the code that you use for training the agent, along with the trained model weights.
a report describing your learning algorithm. This is where you will describe the details of your implementation, along with ideas for future work.