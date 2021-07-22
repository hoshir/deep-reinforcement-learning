# Project 2: Continuous Control

### Environment
The purpose of an agent is to move its hand to the goal location, and keep it there for as many time steps as possible.
Its hand is Double-jointed arm which can move to target locations.
A reward of +0.1 is provided for each step that the agent's hand is in the goal location. 


#### Observations
The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. 

#### Actions
Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

#### Episode
The task is episodic. The environment is considered as solved when an agent gets an average score of +30 over 100
consecutive episodes.

### Getting Started
1. Download the environment from one of the links below.  You need only select the environment that matches your operating system:

    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86_64.zip)

2. Place the file in the same directory of this file (README.md), and unzip (or decompress) the file. 

3. Install Python and dependencies
- Install Python 3.8. (Code **IS NOT** verified in other versions.)
- Install dependencies running the following `pip` command:
  - ```pip install -r requirements.txt```


### Instructions

Follow the instructions in `ReacherApp.ipynb` to get started and training the agent.

