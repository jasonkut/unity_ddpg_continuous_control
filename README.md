# Unity ML Agents - Continuous Control DDPG Solution

![Alt Text](https://github.com/jasonkut/unity_ddpg_continuous_control/raw/master/demo.gif)

### The Environment

In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of the agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1

This code solves the multi-agent version of the environment which has a slightly different barrier, to take into account the presence of many agents (20). In particular, the agents must get an average score of +30 (over 100 consecutive episodes, and over all agents).

### Getting Started

1. Clone and install dependences for the Udacity DeepRL Nanodegree found at [Udacity DeepRL](https://github.com/udacity/deep-reinforcement-learning#dependencies), which are required by this DDPG agent's implementation

2. Download the environment from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86_64.zip)
    
3. Clone this GitHub repository and unzip the Unity continous control environment into its root directory.

### Instructions

- run `Continuous_Control_Solution.ipynb` in Jupyter to train agent!
- run `python demo_agent.py` in terminal to demo agent using pre-trained weights in `checkpoint_actor.pth` & `checkpoint_critic.pth`!

### Notes
These scripts are based on code provided in Udacity's DeepRL Nanodegree
