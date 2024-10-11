---
layout: default
title: Software
---

# Baseline controller family

I am developing open-source humanoid controllers based on the robot control framework [mc_rtc](https://jrl-umi3218.github.io/mc_rtc/).
All of the following controllers are implemented in a unified architecture and enable general baseline motions of humanoids.

## [BaselineWalkingController](https://github.com/isri-aist/BaselineWalkingController)

Humanoid walking controller with various baseline methods.

- [BaselineWalkingControllerに関する日本語ドキュメント](https://gist.github.com/mmurooka/32324ade4ce07d49ae4810c74b235f02)

<video src="https://user-images.githubusercontent.com/6636600/201510077-5be6ab58-9671-413a-93c4-9b84caf9735e.mp4" controls="controls" style="max-width: 640px;">
</video>
<br/>

## [LocomanipController](https://github.com/isri-aist/LocomanipController)

Humanoid loco-manipulation controller.

<video src="https://user-images.githubusercontent.com/6636600/213716066-9f17af4c-4c75-44f7-be30-eb9ba92f4103.mp4" controls="controls" style="max-width: 640px;">
</video>
<br/>

## [MultiContactController](https://github.com/isri-aist/MultiContactController)

Humanoid multi-contact motion controller.

<video src="https://github.com/user-attachments/assets/a50d2b41-d93f-4e4c-8ca2-74fba00e194f" controls="controls" style="max-width: 640px;">
</video>
<br/>

# Baseline planner

## [BaselineFootstepPlanner](https://github.com/isri-aist/BaselineFootstepPlanner)

Humanoid footstep planner based on baseline methods with graph search.

<video src="https://user-images.githubusercontent.com/6636600/187672008-fb93fb0e-5ec0-4054-a31d-68ce6c884005.mp4" controls="controls" style="max-width: 640px;">
</video>
<br/>

# General-purpose controller

## [NMPC](https://github.com/isri-aist/NMPC)

Non-linear model predictive control (NMPC) library.

<video src="https://github.com/isri-aist/NMPC/assets/6636600/02f64c91-88aa-42d8-abfd-f8062d7406e9" controls="controls" style="max-width: 640px;">
</video>
<br/>

# Simulation utilities

## [MujocoRosUtils](https://github.com/isri-aist/MujocoRosUtils)

ROS-based MuJoCo utilities.

<video src="https://github.com/isri-aist/MujocoRosUtils/assets/6636600/6cc3bc6c-113d-4a1d-97f5-d75b1000fc8a" controls="controls" style="max-width: 640px;">
</video>
<br/>

## [MujocoTactileSensorPlugin](https://github.com/isri-aist/MujocoTactileSensorPlugin)

Plugin to simulate tactile sensors in MuJoCo.

<video src="https://github.com/isri-aist/MujocoTactileSensorPlugin/assets/6636600/840652c9-fd7f-472b-9402-442b5498d862" controls="controls" style="max-width: 640px;">
</video>
<br/>

## [CnoidRosUtils](https://github.com/isri-aist/CnoidRosUtils)

ROS-based Choreonoid utilities.

# Visualization utilities

## [RobotArrayVisualization](https://github.com/isri-aist/RobotArrayVisualization)

ROS-based visualization library for robot arrays.

<video src="https://github.com/isri-aist/RobotArrayVisualization/assets/6636600/c20738d6-dc17-4ee6-bec3-03ba152cd238" controls="controls" style="max-width: 640px;">
</video>
<br/>

## [MocapRosUtils](https://github.com/isri-aist/MocapRosUtils)

ROS-based utilities for motion capture.

<video src="https://github.com/isri-aist/MocapRosUtils/assets/6636600/c1c3b077-3f81-42dd-9d78-1073588b167a" controls="controls" style="max-width: 640px;">
</video>
<br/>

# Simulation challenge

- [Humanoid Virtual Athletics Challenge 2021 (AIST-JRL-MM)](https://www.youtube.com/watch?v=shfvDk8zplg&list=PL_MvP6ejFrHu0oTEY-iSzhu6t8Nmu5l-s)

# List of open-source software

| Repository | CI |
| --- | --- |
| [isri-aist/BaselineWalkingController](https://github.com/isri-aist/BaselineWalkingController) <br> ![GitHub Repo stars](https://img.shields.io/github/stars/isri-aist/BaselineWalkingController) ![GitHub Repo watchers](https://img.shields.io/github/watchers/isri-aist/BaselineWalkingController) | [![CI](https://github.com/isri-aist/BaselineWalkingController/actions/workflows/ci.yaml/badge.svg)](https://github.com/isri-aist/BaselineWalkingController/actions/workflows/ci.yaml) |
| [isri-aist/LocomanipController](https://github.com/isri-aist/LocomanipController) <br> ![GitHub Repo stars](https://img.shields.io/github/stars/isri-aist/LocomanipController) ![GitHub Repo watchers](https://img.shields.io/github/watchers/isri-aist/LocomanipController) | [![CI](https://github.com/isri-aist/LocomanipController/actions/workflows/ci.yaml/badge.svg)](https://github.com/isri-aist/LocomanipController/actions/workflows/ci.yaml) |
| [isri-aist/MultiContactController](https://github.com/isri-aist/MultiContactController) <br> ![GitHub Repo stars](https://img.shields.io/github/stars/isri-aist/MultiContactController) ![GitHub Repo watchers](https://img.shields.io/github/watchers/isri-aist/MultiContactController) | [![CI](https://github.com/isri-aist/MultiContactController/actions/workflows/ci.yaml/badge.svg)](https://github.com/isri-aist/MultiContactController/actions/workflows/ci.yaml) |
| [isri-aist/BaselineFootstepPlanner](https://github.com/isri-aist/BaselineFootstepPlanner) <br> ![GitHub Repo stars](https://img.shields.io/github/stars/isri-aist/BaselineFootstepPlanner) ![GitHub Repo watchers](https://img.shields.io/github/watchers/isri-aist/BaselineFootstepPlanner) | [![CI](https://github.com/isri-aist/BaselineFootstepPlanner/actions/workflows/ci-standalone.yaml/badge.svg)](https://github.com/isri-aist/BaselineFootstepPlanner/actions/workflows/ci-standalone.yaml) <br> [![CI](https://github.com/isri-aist/BaselineFootstepPlanner/actions/workflows/ci-catkin.yaml/badge.svg)](https://github.com/isri-aist/BaselineFootstepPlanner/actions/workflows/ci-catkin.yaml) |
| [isri-aist/QpSolverCollection](https://github.com/isri-aist/QpSolverCollection) <br> ![GitHub Repo stars](https://img.shields.io/github/stars/isri-aist/QpSolverCollection) ![GitHub Repo watchers](https://img.shields.io/github/watchers/isri-aist/QpSolverCollection) | [![CI](https://github.com/isri-aist/QpSolverCollection/actions/workflows/ci.yaml/badge.svg)](https://github.com/isri-aist/QpSolverCollection/actions/workflows/ci.yaml) |
| [isri-aist/NMPC](https://github.com/isri-aist/NMPC) <br> ![GitHub Repo stars](https://img.shields.io/github/stars/isri-aist/NMPC) ![GitHub Repo watchers](https://img.shields.io/github/watchers/isri-aist/NMPC) | [![CI-standalone](https://github.com/isri-aist/NMPC/actions/workflows/ci-standalone.yaml/badge.svg)](https://github.com/isri-aist/NMPC/actions/workflows/ci-standalone.yaml) <br> [![CI-catkin](https://github.com/isri-aist/NMPC/actions/workflows/ci-catkin.yaml/badge.svg)](https://github.com/isri-aist/NMPC/actions/workflows/ci-catkin.yaml) |
| [isri-aist/DataDrivenMPC](https://github.com/isri-aist/DataDrivenMPC) <br> ![GitHub Repo stars](https://img.shields.io/github/stars/isri-aist/DataDrivenMPC) ![GitHub Repo watchers](https://img.shields.io/github/watchers/isri-aist/DataDrivenMPC) | [![CI](https://github.com/isri-aist/DataDrivenMPC/actions/workflows/ci.yaml/badge.svg)](https://github.com/isri-aist/DataDrivenMPC/actions/workflows/ci.yaml) |
| [isri-aist/ForceControlCollection](https://github.com/isri-aist/ForceControlCollection) <br> ![GitHub Repo stars](https://img.shields.io/github/stars/isri-aist/ForceControlCollection) ![GitHub Repo watchers](https://img.shields.io/github/watchers/isri-aist/ForceControlCollection) | [![CI-standalone](https://github.com/isri-aist/ForceControlCollection/actions/workflows/ci-standalone.yaml/badge.svg)](https://github.com/isri-aist/ForceControlCollection/actions/workflows/ci-standalone.yaml) <br> [![CI-catkin](https://github.com/isri-aist/ForceControlCollection/actions/workflows/ci-catkin.yaml/badge.svg)](https://github.com/isri-aist/ForceControlCollection/actions/workflows/ci-catkin.yaml) |
| [isri-aist/TrajectoryCollection](https://github.com/isri-aist/TrajectoryCollection) <br> ![GitHub Repo stars](https://img.shields.io/github/stars/isri-aist/TrajectoryCollection) ![GitHub Repo watchers](https://img.shields.io/github/watchers/isri-aist/TrajectoryCollection) | [![CI-standalone](https://github.com/isri-aist/TrajectoryCollection/actions/workflows/ci-standalone.yaml/badge.svg)](https://github.com/isri-aist/TrajectoryCollection/actions/workflows/ci-standalone.yaml) <br> [![CI-catkin](https://github.com/isri-aist/TrajectoryCollection/actions/workflows/ci-catkin.yaml/badge.svg)](https://github.com/isri-aist/TrajectoryCollection/actions/workflows/ci-catkin.yaml) |
| [isri-aist/CentroidalControlCollection](https://github.com/isri-aist/CentroidalControlCollection) <br> ![GitHub Repo stars](https://img.shields.io/github/stars/isri-aist/CentroidalControlCollection) ![GitHub Repo watchers](https://img.shields.io/github/watchers/isri-aist/CentroidalControlCollection) | [![CI-standalone](https://github.com/isri-aist/CentroidalControlCollection/actions/workflows/ci-standalone.yaml/badge.svg)](https://github.com/isri-aist/CentroidalControlCollection/actions/workflows/ci-standalone.yaml) <br> [![CI-catkin](https://github.com/isri-aist/CentroidalControlCollection/actions/workflows/ci-catkin.yaml/badge.svg)](https://github.com/isri-aist/CentroidalControlCollection/actions/workflows/ci-catkin.yaml) |
| [isri-aist/RobotArrayVisualization](https://github.com/isri-aist/RobotArrayVisualization) <br> ![GitHub Repo stars](https://img.shields.io/github/stars/isri-aist/RobotArrayVisualization) ![GitHub Repo watchers](https://img.shields.io/github/watchers/isri-aist/RobotArrayVisualization) | [![CI](https://github.com/isri-aist/RobotArrayVisualization/actions/workflows/ci.yaml/badge.svg)](https://github.com/isri-aist/RobotArrayVisualization/actions/workflows/ci.yaml) |
| [isri-aist/CnoidRosUtils](https://github.com/isri-aist/CnoidRosUtils) <br> ![GitHub Repo stars](https://img.shields.io/github/stars/isri-aist/CnoidRosUtils) ![GitHub Repo watchers](https://img.shields.io/github/watchers/isri-aist/CnoidRosUtils) | [![CI](https://github.com/isri-aist/CnoidRosUtils/actions/workflows/ci.yaml/badge.svg)](https://github.com/isri-aist/CnoidRosUtils/actions/workflows/ci.yaml) |
| [isri-aist/MujocoRosUtils](https://github.com/isri-aist/MujocoRosUtils) <br> ![GitHub Repo stars](https://img.shields.io/github/stars/isri-aist/MujocoRosUtils) ![GitHub Repo watchers](https://img.shields.io/github/watchers/isri-aist/MujocoRosUtils) | [![CI](https://github.com/isri-aist/MujocoRosUtils/actions/workflows/ci.yaml/badge.svg)](https://github.com/isri-aist/MujocoRosUtils/actions/workflows/ci.yaml) |
| [isri-aist/MujocoTactileSensorPlugin](https://github.com/isri-aist/MujocoTactileSensorPlugin) <br> ![GitHub Repo stars](https://img.shields.io/github/stars/isri-aist/MujocoTactileSensorPlugin) ![GitHub Repo watchers](https://img.shields.io/github/watchers/isri-aist/MujocoTactileSensorPlugin) | [![CI](https://github.com/isri-aist/MujocoTactileSensorPlugin/actions/workflows/ci.yaml/badge.svg)](https://github.com/isri-aist/MujocoTactileSensorPlugin/actions/workflows/ci.yaml) |
| [isri-aist/MocapRosUtils](https://github.com/isri-aist/MocapRosUtils) <br> ![GitHub Repo stars](https://img.shields.io/github/stars/isri-aist/MocapRosUtils) ![GitHub Repo watchers](https://img.shields.io/github/watchers/isri-aist/MocapRosUtils) | [![CI](https://github.com/isri-aist/MocapRosUtils/actions/workflows/ci.yaml/badge.svg)](https://github.com/isri-aist/MocapRosUtils/actions/workflows/ci.yaml) |
