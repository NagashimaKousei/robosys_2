# robosys_2
This repository is for performing Task 2 of Robotics Systems.
# usage environment
Raspberry Pi4 4GB
# Explanation
A ROS package that processes data using two publishers and one subscriber.
# List of commands to use
roscore 

chmod +x count.py  

catkin_make

source ~/.bashrc

rosrun mypkg count.py

rosrun mypkg twice.py

rosnode list

rostopic list

rostopic echo /count_up 

rostopic echo /twice

# About installing ROS
Please refer to the link below to install ROS. Execute step0.bash and step1.bash. 
https://github.com/ryuichiueda/ros_setup_scripts_Ubuntu20.04_server
I used it for reference.Thank you to ryuichiueda.
