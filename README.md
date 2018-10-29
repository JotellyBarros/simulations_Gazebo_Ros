
Catkin Workspace configure
-------------
- source ./devel/setup.bash

TURTLEBOT3
-------------

### TURTLEBOT3_MODELs:
- export TURTLEBOT3_MODEL=burger  (Camera);
- export TURTLEBOT3_MODEL=waffle  (Laser Scan);

### Roslaunch Environments
- roslaunch turtlebot3_gazebo turtlebot3_empty_world.launch
- roslaunch turtlebot3_gazebo turtlebot3_autorace.launch 
- roslaunch turtlebot3_gazebo turtlebot3_gazebo_rviz.launch
- roslaunch turtlebot3_gazebo turtlebot3_stage_1.launch
- roslaunch turtlebot3_gazebo turtlebot3_stage_4.launch
- roslaunch turtlebot3_gazebo turtlebot3_autorace_mission.launch
- roslaunch turtlebot3_gazebo turtlebot3_house.launch
- roslaunch turtlebot3_gazebo turtlebot3_stage_2.launch
- roslaunch turtlebot3_gazebo turtlebot3_world.launch
- roslaunch turtlebot3_gazebo turtlebot3_simulation.launch
- roslaunch turtlebot3_gazebo turtlebot3_stage_3.launch 

### Keyboard Teleop
- roslaunch turtlebot3_teleop turtlebot3_teleop_key.launch;

### Visualize Rviz:
- roslaunch turtlebot3_gazebo turtlebot3_gazebo_rviz.launch;


CAMERA STEREO
-------------

### Environments
- roslaunch camera_stereo gazebo.launch 
