# Project 1: Navigation

### Environment

The purpose of an agent is to navigate and collect as many yellow bananas as possible.
A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for
collecting a blue banana.

#### Observations

The state space has 37 dimensions and contains the agent's velocity, along with ray-based
perception of objects around agent's forward direction.

#### Actions
Four discrete actions are available, corresponding to:
- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.

#### Episode
The task is episodic. The environment is considered as solved when an agent gets an average score of +13 over 100
consecutive episodes.

### Getting Started

1. Download the environment from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)

2. Place the file in the same directory of this file (README.md), and unzip (or decompress) the file. 

3. Install Python and dependencies
- Install Python 3.6. (Code **IS NOT** verified in other versions.)
- Install dependencies running the following `pip` command:
  - ```pip install -r requirements.txt```

### Instructions

Follow the instructions in `NavigationBananaApp.ipynb` to get started and training the agent.
