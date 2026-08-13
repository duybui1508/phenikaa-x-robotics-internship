# Training-to-portfolio map

This map converts the 14 training lessons into recruiter-readable competencies. It is not a claim that every lesson was an independently designed project.

| Lesson | Hands-on topic | Portfolio module | What can be stated |
| --- | --- | --- | --- |
| 1 | Dobot Nova 5, DobotStudio Pro, MovJ/MovL, arc/circle, DO-based gripper | Vision and manipulation | Programmed robot motion primitives and I/O pick-and-place sequences |
| 2 | Ubuntu 20.04, ROS Noetic, Catkin, packages, launch files, URDF/Xacro, RViz/Gazebo | ROS 1 AMR | Built and visualized a differential-drive robot model |
| 3 | RealSense L515, image collection, Roboflow annotation, YOLO11, Python/OpenCV | Vision and manipulation | Practiced an OK/NG workpiece detection pipeline |
| 4 | Nova 5 + camera + IPC integration, Modbus TCP/IP registers, target/current poses | System integration | Exchanged robot states and target coordinates for vision-guided manipulation |
| 5 | Forward/inverse kinematics of a two-wheel independently steered system | ROS 1 AMR | Studied forward/inverse kinematics; claim implementation only when code is added |
| 6 | 2D SLAM Toolbox, `/scan`, `/odom`, `/tf`, RViz, map saving | SLAM and navigation | Created and saved a 2D occupancy map in simulation |
| 7 | Differential-drive forward/inverse kinematics, odometry and rqt_plot | ROS 1 AMR | Validated velocity and odometry behavior in Gazebo |
| 8 | `diff_drive_controller`, `ros_control`, `/cmd_vel`, `/odom`, TF | ROS 1 AMR | Configured and controlled a differential-drive model |
| 9 | Costmap, A* and Dijkstra global planners, 2D Nav Goal | SLAM and navigation | Tested and compared A*/Dijkstra planning in simulation |
| 10 | C++ regulated Pure Pursuit controller | SLAM and navigation | Implemented or modified C++ path tracking; publish only personally edited code |
| 11 | BLDC, MD400, MDAS, RS-485, velocity/direction/status monitoring | Industrial control | Configured and operated a BLDC drive through RS-485 |
| 12 | SICK magnetic line sensor, WT901 IMU, RFID, CAN/RS-485 tools | Industrial control | Configured and observed AMR sensor data |
| 13 | Bumper, warning lights, SICK TiM320 fields, E-stop, reset and brake | Industrial control | Configured or tested multilayer AMR safety functions |
| 14 | Delta DVP12SE11T PLC, WPLSoft, HMI, warehouse pick/return sequence | Industrial control | Programmed or tested a PLC/HMI material-handling sequence |

## Claim strength

- **Strong claim:** personal code/configuration plus a working video or repeatable run instructions.
- **Medium claim:** personal screenshot, result file or recorded measurement plus a clear explanation.
- **Training claim:** lesson was completed, but no personal artifact remains. Use wording such as “trained in,” “practiced,” or “gained hands-on experience.”
- **Do not claim:** technologies only mentioned in theory or company code that was merely observed.

