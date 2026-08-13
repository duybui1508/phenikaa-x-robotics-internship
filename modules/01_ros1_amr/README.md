# Module 1 — ROS 1 AMR modeling and control

## Scope

- Created and built a Catkin workspace on Ubuntu 20.04 with ROS Noetic.
- Organized ROS packages, launch files and robot description assets.
- Modeled a differential-drive robot with URDF/Xacro links, joints, visual/collision/inertial properties, transmissions and Gazebo plugins.
- Visualized the robot and TF tree in RViz and simulated it in Gazebo.
- Configured `ros_control` and `diff_drive_controller` to consume `/cmd_vel` and publish `/odom` and `/tf`.
- Validated robot velocity with `rqt_plot` and displacement with `rostopic echo /odom`.
- Studied forward/inverse kinematics for differential drive and a two-wheel independently steered system.

## Artifacts to add

```text
src/
  robot_description/
  differential_drive_robot_gazebo/
config/
  diff_drive_controller.yaml
launch/
media/
  robot_rviz.png
  robot_gazebo.png
```

Only add files personally authored or cleared for publication.

## Minimum evidence

- URDF/Xacro source.
- RViz and Gazebo screenshots.
- 20–30 second driving clip.
- One plot showing commanded versus observed velocity or odometry.

