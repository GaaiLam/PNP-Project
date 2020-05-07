# PNP Project

#### Project Assignments

Three assignments are required for this project including:

1. Calculating the camera’s pose corresponding to every image.
2. Publishing camera pose information in the form of nav msgs/Odometry.
3. Plotting these poses with **rqt_rviz**.
4. Comparing your result with the reference.

#### Project Setup

You will be provided with a ROS package named tag detector, where a serial of points and their positions be calculated with images. You need to implement this project based on the point and position array. You can the below procedures to prepare for your coding.

1. download the [release package](https://github.com/MarkSoviet/PNP-Project/releases/download/0.1/PNP-Project.zip).
2. put aruco-1.2.4 and tag detector in your workspace (catkin ws/src/)
3. install aruco (following aruco-1.2.4/README)
4. Setup your ROS environment and compile the tag detector package.
5. Find bag_tag.launch in tag detector/launch, and images.bag in tag_detector/bag.
6. Use bag_tag.launch and images.bag to run this package (roslaunch bag_tag.launch).
7. Read the comments in tag detector/src/tag_detector node.cpp carefully.
8. Add your code into tag_detector/src/tag_detector_node.cpp