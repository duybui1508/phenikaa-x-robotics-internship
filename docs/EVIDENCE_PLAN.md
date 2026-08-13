# Evidence plan

## Priority 1 — flagship vision-guided manipulation demo

**Target length:** 60–90 seconds.

Show, in one continuous sequence:

1. RealSense RGB/depth stream and the physical workpiece.
2. YOLO11 overlay with class `OK` or `NG`, confidence and detected pose/orientation.
3. Redacted terminal or dashboard showing that the target data was transmitted.
4. Dobot Nova 5 moving to the safe point, picking the workpiece and placing it in the correct tray.
5. A second workpiece from the other class, if time permits.

Add a short caption stating the personal contribution: camera pipeline, robot program, integration or testing. Do not display internal IP addresses or credentials.

**Why mandatory:** this is the most distinctive piece of the internship. Without the video, the strongest CV bullet is difficult to verify.

## Priority 2 — ROS 1 autonomy demo

**Target length:** 60–90 seconds.

Show a split or sequential recording of Gazebo and RViz:

1. Launch the differential-drive AMR in the maze world.
2. Display RobotModel, LaserScan, map, TF and planned path in RViz.
3. Run SLAM Toolbox and drive the robot long enough to show the map expanding.
4. Set a `2D Nav Goal` and show A* planning plus robot motion.
5. Repeat with Dijkstra or show a side-by-side path comparison.
6. Show Pure Pursuit tracking a planned path and reaching the goal.

Useful commands to display briefly:

```bash
roslaunch amr_startup maze.launch
rosservice call /gazebo/unpause_physics
roslaunch slam_toolbox online_async.launch
roslaunch amr_startup start_global_planner.launch global_planner:=astar
roslaunch amr_startup start_global_planner.launch global_planner:=dijkstra
roslaunch amr_startup start_planner.launch
```

Also add:

- A screenshot of the URDF model in RViz.
- A screenshot of `/odom` or `rqt_plot` while the robot moves.
- One saved `.yaml` map and a preview image. Raw `.pgm` maps are ignored by default; add a small `.png` preview instead.

**Why mandatory:** the repository is intended to prove ROS 1/AMR competence. A README without a running robot is just decorative wallpaper.

## Priority 3 — PLC/HMI warehouse demo

**Target length:** 30–60 seconds.

Show the HMI start command, actuator sequence, limit-sensor transitions, successful pick/return and cycle completion. If available, include one safety interruption and safe recovery.

Record the cycle time and success rate over multiple runs. These two numbers create a much stronger CV result than merely listing PLC and HMI.

## Evidence matrix

| Topic | Code/config | Screenshot | Video | Priority |
| --- | --- | --- | --- | --- |
| URDF/Xacro AMR model | Required | Required | Short clip | High |
| Differential-drive control and odometry | Required | Required | Optional if included in autonomy demo | High |
| SLAM map creation | Launch/config | Map preview | Required as part of autonomy demo | High |
| A*/Dijkstra planning | Planner config/source | Path comparison | Required as part of autonomy demo | High |
| Pure Pursuit C++ | Personally edited source | Tracking plot/path | Required as part of autonomy demo | High |
| Dobot Nova motion and I/O | Export or recreated sequence | Program view | Required as part of flagship demo | High |
| YOLO11 OK/NG detection | Inference code and metrics | Confusion matrix/results | Required | High |
| Modbus integration | Redacted register map/config | State/target log | Included in flagship demo | High |
| BLDC/MD400 over RS-485 | Redacted settings | MDAS velocity plot | 15–20 second clip | Medium |
| Magnetic sensor, IMU and RFID | Redacted config/log | Data plots/reader output | Optional compilation clip | Medium |
| TiM320 safety fields and E-stop | Redacted field screenshot | Three-zone response | Strongly recommended | Medium |
| PLC/HMI pick-and-return | Personal project files if allowed | HMI screen | Required for industrial roles | Medium/high |
| 2WIDS equations | Personal derivation or code | Plot/test table | Only if implemented | Low |

