# VEX Autonomous Programming

## Overview

For the REC Foundation VEX Robotics Competition (REC), our autonomous programming is divided into two categories:

- **Alliance Autonomous:** Designed for competition matches, where our robot works alongside an alliance partner.
- **Solo Autonomous:** Designed for individual skills runs.

## Current Alliance Autonomous Strategy

My current alliance autonomous strategy consists of:

1. Scoring a preload.
2. Scoring a stack.
3. Attempting to toggle the neutral goal.

The goal is to execute these actions consistently while maximizing scoring opportunities during the autonomous period.

## Current Challenges & Improvements

One current challenge is accurately determining which alliance color the robot will be on when attempting to toggle the neutral goal.

At the moment, this is somewhat of a guessing game. To improve reliability and precision, I plan to implement a VEX Optical Sensor to detect the relevant color and help determine the correct toggling action.

## Robot Sensors

Our robot currently uses two sensors:

| Sensor | Purpose |
|---|---|
| VEX V5 Inertial Sensor | Used for PID control and improving movement precision. |
| VEX Optical Sensor | Planned for color detection and more precise neutral-goal toggling. |

## Development Status

This project is actively being developed throughout the competition season.

I plan to upload the C++ source code to this repository after the competition season ends. Until then, this README documents the current strategy, hardware, challenges, and planned improvements.
