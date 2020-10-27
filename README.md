## Description 
AIDA is a high-fidelity simulator of Gazebo, which is designed for low-cost biped locomotion tasks. 

AIDA enables the use of existing reinforcement learning and control algorithms to teach robots how to walk in a stable pattern.

The Env folder contains the robot model and the ground model. The RL controller is located in the Controller folder.

## Requirements
[ROS kinetic](http://wiki.ros.org/kinetic/Installation/Ubuntu)  
[Pytorch](https://pytorch.org/get-started/locally/)

## Usage
### Getting Started
Open a terminal and launch AIDA environment: 
```
roslaunch PATH_TO/aida_gazebo/launch/robotis_env_aida.launch
```
### Launch controller
#### Testing the RL controller
Launch the RL agent to control the robot to walk.
```
python rl_controller.py
```
## Features
### Bipedal robot model
### 4 walking tasks
### Metrics
