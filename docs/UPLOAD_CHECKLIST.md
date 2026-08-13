# Artifact collection checklist

Collect these items before publishing the repository.

## ROS workspace

- Copy only `amr_simulation_ws/src/`.
- Do not copy `build/`, `devel/`, `install/`, `log/` or rosbag files.
- Include `package.xml`, `CMakeLists.txt`, launch files, URDF/Xacro, controller YAML and personally edited C++/Python nodes.
- Add a dependency list and clean run instructions from a fresh terminal.
- Confirm whether the starter packages may legally be redistributed. If not, publish a small independent recreation or a patch showing only personal work.

## Vision and robot arm

- Personal Python inference/integration code.
- Dataset description and class names, but not restricted raw company images.
- Training metrics: precision, recall, mAP, confusion matrix and representative inference images.
- Dobot program export or an independently recreated block diagram.
- A redacted Modbus register summary without internal network details.

## Industrial control

- Personal PLC/HMI project only if sharing is permitted.
- Redacted wiring sketches and device configuration screenshots.
- BLDC velocity response plot.
- Sensor logs or screenshots for magnetic line, IMU and RFID tests.
- TiM320 field configuration screenshot with all facility details removed.

## Media

- Record landscape 1080p when possible.
- Keep each video under 90 seconds.
- Use filenames such as `ros1_navigation_demo.mp4` and `vision_pick_place_demo.mp4`.
- Add subtitles naming the input, algorithm and result.
- Blur faces, badges, serial numbers, credentials, network settings and confidential equipment.

## Final checks

- Every CV bullet points to at least one artifact.
- Every command in a README has been rerun successfully.
- No empty “Results” section remains.
- No original training Word files are committed.
- The repository is public and viewable while signed out of GitHub.

