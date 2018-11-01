##### Start Workspace
```
$ source ./devel/setup.bash
```
##### TURTLEBOT3
-------------
##### Start the TURTLEBOT3 MODEL:
```
$ export TURTLEBOT3_MODEL=burger  (Camera)
```
##### Start Roslaunch Environments
```
$ roslaunch turtlebot3_gazebo turtlebot3_empty_world.launch
```
##### Start Roslaunch Environment with Camera
```
$ roslaunch turtlebot3_gazebo turtlebot3_autorace.launch
```
##### Start Keyboard Teleop
```
$ roslaunch turtlebot3_teleop turtlebot3_teleop_key.launch
```
##### Start Visualize Rviz:
```
$ roslaunch turtlebot3_gazebo turtlebot3_gazebo_rviz.launch
```
##### CAMERA STEREO
-------------
##### Start Roslaunch Environments
```
$ roslaunch camera_stereo gazebo.launch
```
