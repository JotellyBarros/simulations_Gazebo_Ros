source ./devel/setup.bash

-----------------------------------turtlebot3------------------------------

export TURTLEBOT3_MODEL=burger
or
export TURTLEBOT3_MODEL=waffle

roslaunch turtlebot3_gazebo turtlebot3_autorace.launch 

roslaunch turtlebot3_teleop turtlebot3_teleop_key.launch 

-----------------------------------camera_stereo---------------------------

roslaunch camera_stereo gazebo.launch 
