# Workshop: Exploring AR-enabled Human-Robotic Collaboration System for Collaborative Assembly Tasks.

## CAADRIA 2024 @ Singapore University of Technology And Design

> 20-22 April 2021

![Flyer](images/spatial_robotic_assembly.jpg)

👉 [Slides](https://docs.google.com/presentation/d/1XioagUYqCVWCgxudyw0m4pQa-cu9_5Pf7duuSE7PYMo) | [Overview](#overview) | [Examples](examples/) | [Requirements](#requirements) | [Installation](#installation)

## Overview

### Day 1

* Introduction to digital fabrication.
* Overview of COMPAS framework.
* Fundamental concepts of robotics: components of an industrial robot, robot workspace, control modes, robot positioning (cartesian and joint space) and singularities, robot coordinate frames and transformations.
* Description of robot models, the URDF format, visualizing robot models, interop with external model sources. Grasshopper integration. Exercise: build your own robot model.
* Forward Kinematics (in-process and out-process) and Inverse Kinematics (overview of analytic and numerical solvers).

### Day 2

* Overview of supported robotic backends.
* ROS: Robot Operating System and the MoveIt! Motion planning framework. ROS communication model: topics, services and actions.
* Path planning: Cartesian and kinematic path planning from Rhino and Grasshopper using MoveIt backend. Defining goal constraints.
* Planning scene manipulation. Dynamic end-effector attachment and detachment.
* Describing assembly processes in code. Basic structure of a pick and place process. Approach frames. Overview of advanced assembly structures: graphs/partial orders/networks.
* Fabrication-aware design: the impact of sequencing in spatial assembly processes.
* Exercise: path planning of a simple assembly structure.

### Day 3

* ABB robot control with RRC.
* Comparison of robot control modes: offline, online real-time, online non-real-time control.
* RRC control primitives: blocking, non-blocking, and deferred blocking.
* Overview of RRC instruction set: motion, IO control, custom instructions.
* Remote control exercise with one of the robots of the Robotic Fabrication Lab at ETH Zurich.

## Requirements

* Minimum OS: Windows 10/11
* [Rhino 7/8 & Grasshopper](https://www.rhino3d.com/download)

## Installation

We use Rhinoceros 3D and Grasshopper to communicate with the cooperative robotic arm, UR10.
We use grasshopper plugin such as “Robot” to establish connection with the UR10, and  fologram plugin to establish a mixed reality platform.

