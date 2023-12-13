---
layout: default
title: Software
---

# Baseline controller family

I am developing open-source humanoid controllers based on the robot control framework [mc_rtc](https://jrl-umi3218.github.io/mc_rtc/).
All of the following controllers are implemented in a unified architecture and enable general baseline motions of humanoids.

## [BaselineWalkingController](https://github.com/isri-aist/BaselineWalkingController)

Humanoid walking controller with various baseline methods.

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

<video src="https://user-images.githubusercontent.com/6636600/220029546-ef3d5e66-c06d-417e-aac3-27832299f216.mp4" controls="controls" style="max-width: 640px;">
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

# Status of continuous integration (CI)

| Repository | CI |
| --- | --- |
| [isri-aist/QpSolverCollection](https://github.com/isri-aist/QpSolverCollection) | [![CI](https://github.com/isri-aist/QpSolverCollection/actions/workflows/ci.yaml/badge.svg)](https://github.com/isri-aist/QpSolverCollection/actions/workflows/ci.yaml) |
| [isri-aist/NMPC](https://github.com/isri-aist/NMPC) | [![CI-standalone](https://github.com/isri-aist/NMPC/actions/workflows/ci-standalone.yaml/badge.svg)](https://github.com/isri-aist/NMPC/actions/workflows/ci-standalone.yaml) [![CI-catkin](https://github.com/isri-aist/NMPC/actions/workflows/ci-catkin.yaml/badge.svg)](https://github.com/isri-aist/NMPC/actions/workflows/ci-catkin.yaml) |
| [isri-aist/DataDrivenMPC](https://github.com/isri-aist/DataDrivenMPC) | [![CI](https://github.com/isri-aist/DataDrivenMPC/actions/workflows/ci.yaml/badge.svg)](https://github.com/isri-aist/DataDrivenMPC/actions/workflows/ci.yaml) |
| [isri-aist/CnoidRosUtils](https://github.com/isri-aist/CnoidRosUtils) | [![CI](https://github.com/isri-aist/CnoidRosUtils/actions/workflows/ci.yaml/badge.svg)](https://github.com/isri-aist/CnoidRosUtils/actions/workflows/ci.yaml) |
| [isri-aist/ForceControlCollection](https://github.com/isri-aist/ForceControlCollection) | [![CI-standalone](https://github.com/isri-aist/ForceControlCollection/actions/workflows/ci-standalone.yaml/badge.svg)](https://github.com/isri-aist/ForceControlCollection/actions/workflows/ci-standalone.yaml) [![CI-catkin](https://github.com/isri-aist/ForceControlCollection/actions/workflows/ci-catkin.yaml/badge.svg)](https://github.com/isri-aist/ForceControlCollection/actions/workflows/ci-catkin.yaml) |
| [isri-aist/TrajectoryCollection](https://github.com/isri-aist/TrajectoryCollection) | [![CI-standalone](https://github.com/isri-aist/TrajectoryCollection/actions/workflows/ci-standalone.yaml/badge.svg)](https://github.com/isri-aist/TrajectoryCollection/actions/workflows/ci-standalone.yaml) [![CI-catkin](https://github.com/isri-aist/TrajectoryCollection/actions/workflows/ci-catkin.yaml/badge.svg)](https://github.com/isri-aist/TrajectoryCollection/actions/workflows/ci-catkin.yaml) |
| [isri-aist/CentroidalControlCollection](https://github.com/isri-aist/CentroidalControlCollection) | [![CI-standalone](https://github.com/isri-aist/CentroidalControlCollection/actions/workflows/ci-standalone.yaml/badge.svg)](https://github.com/isri-aist/CentroidalControlCollection/actions/workflows/ci-standalone.yaml) [![CI-catkin](https://github.com/isri-aist/CentroidalControlCollection/actions/workflows/ci-catkin.yaml/badge.svg)](https://github.com/isri-aist/CentroidalControlCollection/actions/workflows/ci-catkin.yaml) |
| [isri-aist/BaselineFootstepPlanner](https://github.com/isri-aist/BaselineFootstepPlanner) | [![CI](https://github.com/isri-aist/BaselineFootstepPlanner/actions/workflows/ci-standalone.yaml/badge.svg)](https://github.com/isri-aist/BaselineFootstepPlanner/actions/workflows/ci-standalone.yaml) [![CI](https://github.com/isri-aist/BaselineFootstepPlanner/actions/workflows/ci-catkin.yaml/badge.svg)](https://github.com/isri-aist/BaselineFootstepPlanner/actions/workflows/ci-catkin.yaml) |
| [isri-aist/BaselineWalkingController](https://github.com/isri-aist/BaselineWalkingController) | [![CI](https://github.com/isri-aist/BaselineWalkingController/actions/workflows/ci.yaml/badge.svg)](https://github.com/isri-aist/BaselineWalkingController/actions/workflows/ci.yaml) |
| [isri-aist/LocomanipController](https://github.com/isri-aist/LocomanipController) | [![CI](https://github.com/isri-aist/LocomanipController/actions/workflows/ci.yaml/badge.svg)](https://github.com/isri-aist/LocomanipController/actions/workflows/ci.yaml) |
| [isri-aist/MultiContactController](https://github.com/isri-aist/MultiContactController) | [![CI](https://github.com/isri-aist/MultiContactController/actions/workflows/ci.yaml/badge.svg)](https://github.com/isri-aist/MultiContactController/actions/workflows/ci.yaml) |
| [isri-aist/MujocoRosUtils](https://github.com/isri-aist/MujocoRosUtils) | [![CI](https://github.com/isri-aist/MujocoRosUtils/actions/workflows/ci.yaml/badge.svg)](https://github.com/isri-aist/MujocoRosUtils/actions/workflows/ci.yaml) |
| [isri-aist/MujocoTactileSensorPlugin](https://github.com/isri-aist/MujocoTactileSensorPlugin) | [![CI](https://github.com/isri-aist/MujocoTactileSensorPlugin/actions/workflows/ci.yaml/badge.svg)](https://github.com/isri-aist/MujocoTactileSensorPlugin/actions/workflows/ci.yaml) |
