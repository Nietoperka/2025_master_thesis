# "Controlling a collaborative robot using gestures"
autor: Agnieszka Osińska

## ABSTRACT:
The purpose of this thesis was to design and implement a system that allows the control of a collaborative robotic arm using user gestures. A literature review compared existing solutions, selecting YOLOv8 as the tool for body keypoint detection. The system was integrated with ROS 2 Humble and MoveIt, creating a node that analyzes hand, elbow and shoulder positions. Based on these, motion trajectories were generated for the robot's two joints, ensuring smooth control. The system was equipped with safety mechanisms and reaction time measurement. As part of the research, the accuracy of gesture recognition and the robot's response latency were tested. High performance and low latency were achieved, confirming intuitive and reliable operation. The system demonstrated noise immunity and stability in the test environment. The developed solution can be used in industrial and service applications requiring non-contact robot control. The work provides a basis for further development of human-robot interaction systems based on computer vision.
### Keywords:
HRI, human–robot interaction, YOLO, ROS 2, MoveIt, collaborative robot, keypoint detection, deep learning, joint trajectory.

## Hardware
🦾 Collaborative robot [Hanwha HCR-3A](https://www.hycobot.com/hcr-3) <br />
📷 Camera [Intel® RealSense™ D435](https://www.intelrealsense.com/depth-camera-d435/)<br />

## Software
🐧 Linux Ubuntu 22.04 LTS Jammy Jellyfish<br />
🤖 ROS 2 Humble Hawksbill<br />
👁️ [YOLOv8](https://github.com/mgonzs13/yolo_ros/tree/main)<br />
