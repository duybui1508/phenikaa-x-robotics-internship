# Module 3 — AI vision and Dobot Nova 5 manipulation

## Scope

- Connected and operated a Dobot Nova 5 through DobotStudio Pro.
- Created joint, linear, arc and circular trajectories using taught points.
- Controlled a gripper through digital output for pick-and-place sequences.
- Captured RGB/depth data with Intel RealSense L515.
- Annotated OK/NG workpiece images in Roboflow and trained a YOLO11 detector with Ultralytics.
- Used Python, `pyrealsense2` and OpenCV to stream data, run inference and estimate workpiece position/orientation.
- Practiced Modbus TCP/IP exchange of robot state, current/target pose, classification and motion-complete signals.

## Artifacts to add

```text
camera/
  capture.py
  infer.py
  pose_estimation.py
robot/
  README.md
integration/
  modbus_client.py
  register_map_redacted.md
metrics/
  confusion_matrix.png
  results.png
media/
  vision_pick_place_demo.mp4
```

## Results to report

- Number of training/validation images.
- Precision, recall and mAP from the final model.
- Inference speed on the deployment computer.
- Pick-and-place success rate across repeated trials.

The end-to-end video is mandatory before using the strongest CV bullet.

