# raicam_first_demo
You'll find the ROBOTNIK platform simulation files and installation/setup instructions here.

## How to install the robotnik simulation 

1. Clone "https://github.com/RobotnikAutomation/robotnik_msgs.git"

2. Clone "https://github.com/RobotnikAutomation/robotnik_sensors.git"

3. Clone "https://github.com/RobotnikAutomation/summit_xl_common.git" FOR ME NOETIC-DEVEL, find the proper branch for yourself

4. Clone "https://github.com/RobotnikAutomation/summit_xl_sim.git" FOR ME NOETIC-DEVEL, find the proper branch for yourself

# What else to install
1. sudo apt install ros-noetic-mavros-msgs
2. sudo apt install ros-noetic-velocity-controllers
3. sudo apt install ros-noetic-robot-localization


# How to Launch

1. roslaunch summit_xl_sim_bringup summit_xls_complete.launch

## Demo World, 

1. In the launch file "summit_xls_complete.launch" search  for world and change the arg to demo.world

2. also you need to change the map which has the prefix of .yaml in the same launch file

3. In this repository changes in the launch file for summit_xl_sim has already been made and as an example three obstacles have been added to the the world, you can use it to add more or remove it, try to clone the repository and take a look into 

summit_xls_complete.launch

4. The obstacles are written in the demo.world and are not in the map of course.







