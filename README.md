# Phenikaa-X Robotics Internship Portfolio

Hands-on robotics and industrial automation work completed during an internship training program at Phenikaa-X.

The portfolio focuses on four practical areas:

1. ROS 1 mobile robot modeling, simulation and control.
2. SLAM, global path planning and path tracking for autonomous mobile robots.
3. AI vision and Dobot Nova 5 manipulation.
4. Industrial communication, sensors, safety, PLC and HMI integration.

> Evidence status: the repository structure and technical summaries are ready. Personal source code, screenshots and demo videos still need to be added before this repository should be linked in a CV.

## Technical stack

- Ubuntu 20.04, ROS Noetic, Catkin
- C++, Python
- Gazebo, RViz, rqt, ros_control, diff_drive_controller
- URDF/Xacro, TF, Odometry, LiDAR, SLAM Toolbox
- A*, Dijkstra, Pure Pursuit
- Dobot Nova 5, DobotStudio Pro, Blockly, digital I/O
- Intel RealSense L515, OpenCV, Roboflow, Ultralytics YOLO11
- Modbus TCP/IP, RS-485, CAN, PLC Delta, HMI
- BLDC/MD400, magnetic line sensor, IMU, RFID, SICK TiM320

## Portfolio modules

| Module | What was practiced | Evidence to add |
| --- | --- | --- |
| [ROS 1 AMR](modules/01_ros1_amr/README.md) | Catkin workspace, URDF/Xacro model, Gazebo/RViz, differential-drive control, odometry | Source package, model screenshot, short simulation video |
| [SLAM and navigation](modules/02_slam_navigation/README.md) | 2D mapping, saved maps, A*/Dijkstra planning, Pure Pursuit tracking | Map files, planner code, RViz/Gazebo demo video |
| [AI vision and manipulation](modules/03_vision_manipulation/README.md) | Nova 5 motion/I/O, RealSense acquisition, YOLO11 OK/NG detection, Modbus integration | Training metrics, inference code, flagship pick-and-place video |
| [Industrial control and safety](modules/04_industrial_control/README.md) | BLDC over RS-485, AMR sensors, safety fields, PLC/HMI warehouse sequence | Wiring/config screenshots and physical-system demo |

## Recommended demos

The three strongest demonstrations are listed in [docs/EVIDENCE_PLAN.md](docs/EVIDENCE_PLAN.md):

1. Vision-guided Nova 5 pick-and-place with OK/NG classification.
2. ROS Noetic AMR mapping, navigation and path tracking in Gazebo/RViz.
3. PLC/HMI-controlled warehouse pick-and-return cycle with safety behavior.

Do not link this repository in a CV until at least demos 1 and 2 have evidence.

## CV wording

Recruiter-ready English and Vietnamese bullet points are in [docs/CV_BULLETS.md](docs/CV_BULLETS.md). They are deliberately written to describe hands-on internship training without claiming ownership of the complete Phenikaa-X platform.

## Repository policy

- Only personal implementations, redacted configurations and self-recorded media belong here.
- Original training documents, company source code, credentials, internal IP addresses and proprietary diagrams must not be published.
- Large model weights, rosbag files and raw datasets should use Git LFS or external release storage only when sharing is permitted.
- See [NOTICE.md](NOTICE.md) before uploading artifacts.

