# VADER Common ROS messages

## Attribution

This repository belongs to Carnegie Mellon University, Masters of Science - Robotic Systems Development (MRSD) Team E - VADER

Team Members: Tom Gao, Abhishek Mathur, Rohit Satishkumar, Kshitij Bhat, Keerthi GV 

First Revision: February 2025

## Introduction and Overview

This is a repository containing the inter-subsystem ROS message definitions for the project. 

## How to use

This repository should be placed inside the src/ folder in your workspace. Catkin should then be able to build this package alongside the source of other subsystem packages.

## How to make a new message

Refer to existing messages/service calls and add your new message types in CMakeLists.txt. Add any dependencies accordingly.