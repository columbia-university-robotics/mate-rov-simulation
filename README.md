# MATE ROV LAUNCH INSTRUCTIONS

![ Mate ROV simulation ](./media/mate_rov_demo.gif)

Welcome to the MATE simulation repository, developed by Columbia University Robotics Club. This repo contains the source code for simulating our underwater vehicle using ROS and Gazebo.

* Note : this simulation is currently heavily inspired from https://github.com/NishanthARao/ROS-Quadcopter-Simulation , it's a very nice simulation base so please see how the simulation started at your own leisure. 

# Getting Started

To start using our simulation system, you can follow the instructions provided in this document.
```
cd ~/workspace/mate-rov/2020_workspace
catkin_make
source devel/setup.bash
roslaunch mate_simulation mate_rov_gazebo.launch
```
Make sure you click the terminal you just launched when you want to use the keyboard to control the ROV.

You should now be able to control the ROV :) enjoy


* WARNING : WE DO NOT HAVE ANY LIMITS ON THE PROPELLOR VALUES, press and let the buttons go to avoid sending an absurdly high signal to the propellors. 

```
Moving around:
        w         r               i         
   a    s    d    f           j   k   l
   z         c


w/s : Z-axis  up/down 
a/d : yaw   left/right
z/c : roll   ccw/cw
r/f : pitch   up/down
i/k :    forward/reverse
j/l : truck left/right 

anything else : stop

CTRL-C to quit the keyboard control and then one more time to close the simulation
```


For any questions, comments, or concerns, please don't hesitate to reach out to us at [curc@columbia.edu](curc@columbia.edu). If you are a current member of CURC and would like to contribute to the repository, please reach out to Jonathan or Neil via email or Slack.

# About Us

We are the Columbia University Robotics Club, a student-run organization that develops robots and autonomous systems, both in a competitive and research setting. MATE ROV is an annual underwater vehicle challenge that we participate in. To learn more about our club, please visit columbiaroboticsclub.com





