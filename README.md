# RoboND-Localization-Project
This project uses implementation of particle filter localization algorithm in ROS called Adaptive Monte Carlo Localization (AMCL). This algorithm was used to estimate and track poses of the two (2) different simulated mobile robots relative to a known map of an environment while they navigate through the map.


### How to clone this repository
```
$ cd ~/catkin_ws/src

$ git clone https://github.com/salabson/RoboND-Localization-Project.git
```

### How to use this repository

**Terminal 1**
```
$ cd ~/catkin_ws/
$ source devel/setup.bash
$ roslaunch udacity_bot udacity_world.launch
```
**Terminal 2**
```
$ cd ~/catkin_ws/
$ source devel/setup.bash
$ roslaunch udacity_bot amcl.launch
```

**Terminal 3**
```
$ cd ~/catkin_ws/
$ source devel/setup.bash
$ rosrun udacity_bot navigation_goal
```
