# VADER Common ROS messages

A repository containing the inter-subsystem ROS message definitions for the project. 

## How to use

This repository shall be submoduled in other subsystem github repositories, and should be placed inside the src/ folder in those repositories. catkin should then be able to build this package alongside the source of other subsystem packages.

## How to make a new message

Refer to example.msg, and add your new message type in CMakeLists.txt. Add any dependencies accordingly.