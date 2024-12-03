# RobotV_Fall-alarm-monitoring
Fall alarm monitoring ROS intelligent car

Remote login

ssh -Y  wheeltec@192.168.0.100

Input password

WiFi password: 12345678

Enter Linux password

Virtual machine system password: 123

Open ROS master node

roscore

Activate the depth camera

roslaunch astra_camera astra.launch

Start calling YOLOv5 to implement recognition

rosrun yolov5_track yolov5_track.py
