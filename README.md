[//]: # (Image References)

[image1]: https://video.udacity-data.com/topher/2018/June/5b1ea778_reacher/reacher.gif "Reacher Agent"


# Continuous-Control
For this project, we work with the Reacher environment.

![Reacher Agent][image1]

*Unity ML-Agents Reacher Environment*


Double-jointed arms can move to specific locations within this environment. Each time the agent's hand reaches the goal location, the agent receives a reward of +0.1. As a result, the agent's goal is to maintain its position at the target location for the maximum number of time steps.

The observation space comprises 33 variables representing the arm's position, rotation, velocity, and angular velocities. In each action, there are four numbers, each corresponding to torque applied to two joints. In the action vector, each entry should be a number between -1 and 1.

## The purpose of this project:

This project aims to develop a training agent for controlling a robotic arm within Unity's Reacher environment. It is the objective to maintain contact with the green spheres with the help of a robotic arm.

### Getting Started


1. Clone the repository git clone (https://github.com/Sebelandanishvar/Continuous-Control.git)

    To set up your Python environment, please follow the instructions in the DRLND GitHub repository (https://github.com/udacity/deep-reinforcement-    learning#dependencies). PyTorch, ML-Agents, and several other Python packages are required to complete this project.

2. Please click on one of the links below to download the environment. The only thing you need to do is select the appropriate environment for your operating system:    
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
    
    (_For Windows users_) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

    (_For AWS_) If you'd like to train the agent on AWS (and have not [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip) to obtain the environment.

3. Unzip (or decompress) the file in the 'p2_continuous-control/folder' in the DRLND GitHub repository. 

### Instructions

Follow the instructions in `Continuous_Control.ipynb` and feel free to get started with training your own agent!  
