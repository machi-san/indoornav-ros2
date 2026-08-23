# indoornav-ros2

ROS2 Perception + SLAM portfolio project — porting the Indoor Navigation System for
Visually Impaired Users (EfficientDet-Lite0 + ultrasonic sensor fusion) into a full ROS2
software stack, and extending prior UGV mapping experience into a working SLAM
implementation. Built to close a ROS2/Gazebo skill gap identified in target robotics job
postings.

See the related capstone project: [https://github.com/machi-san/indoornav]

Setup verified Sat Aug 22 20:04:41 +04 2026

## Progress

- [x] **Phase 1 — Environment setup**: WSL2 + Ubuntu 22.04, ROS2 Humble, Gazebo Classic,
  TurtleBot3 simulation packages, slam_toolbox, and Nav2 installed and verified. Confirmed
  by successfully launching the TurtleBot3 Gazebo simulation.
- [x] **Phase 2 — ROS2 fundamentals**: built a custom `ament_python` package
  (`py_pubsub_practice`) implementing a minimal publisher/subscriber pair from scratch, to
  learn ROS2's core node/topic communication pattern before applying it to real sensor and
  perception data.
- [ ] **Phase 3 — Port Indoor Navigation**: restructure the existing detection + sensor
  fusion logic into ROS2 nodes
- [ ] **Phase 4 — Simulate the full pipeline in Gazebo**
- [ ] **Phase 5 — SLAM mapping**
- [ ] **Phase 6 — Document, record, and publish**

## Stack

ROS2 Humble · Gazebo Classic · TurtleBot3 · slam_toolbox · Nav2 · Python (rclpy) ·
TensorFlow Lite · OpenCV