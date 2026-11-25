# robot-arm-moveit2
# MoveIt 2 Robot Arm

Robotic arm project using ROS 2 and MoveIt 2, developed alongside a Udemy course.

## Setup

- ROS 2 distribution: <Jazzy>
- Arm model and degrees of freedom: <TBD>
- Course reference: <TBD>

## Build

Run from the workspace root with your ROS 2 environment sourced:

    rosdep install --from-paths src --ignore-src -r -y
    colcon build --symlink-install
    source install/setup.bash

## Run

    TBD