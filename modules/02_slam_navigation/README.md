# Module 2 — SLAM, planning and path tracking

## Scope

- Consumed LiDAR `/scan`, odometry `/odom` and TF data for 2D mapping.
- Used SLAM Toolbox in ROS Noetic to generate and save an occupancy-grid map.
- Worked with costmaps and global navigation architecture.
- Tested A* and Dijkstra global planners from RViz `2D Nav Goal` inputs.
- Implemented or modified a regulated Pure Pursuit controller in C++ and tested path tracking in Gazebo.

## Artifacts to add

```text
config/
  slam_toolbox.yaml
  global_costmap.yaml
  local_costmap.yaml
maps/
  map.yaml
  map_preview.png
src/
  global_planner/
  regulated_pure_pursuit_controller/
media/
  astar_vs_dijkstra.png
  ros1_navigation_demo.mp4
```

## Results to report

- Map environment and approximate area.
- Path length or planning time for A* and Dijkstra under the same start/goal.
- Goal-position error and path-tracking behavior for Pure Pursuit.
- Parameters personally tuned, such as look-ahead distance or velocity limits.

Do not report invented metrics. Add measurements only after rerunning the demos.

