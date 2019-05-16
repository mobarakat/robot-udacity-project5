# robot-udacity-project5
_Robotics Software Engineer Nanodegree Program: Project 5_

[![Udacity - Robotics NanoDegree Program](https://s3-us-west-1.amazonaws.com/udacity-robotics/Extra+Images/RoboND_flag.png)](https://www.udacity.com/robotics)

## Description

### "Home Service Robot" Project

A home service robot that will automously map an enviroment and navigate to pickup and deliver objects. That happens as following:

* Initially show the marker at the pickup zone
* Hide the marker once your robot reaches the pickup zone
* Wait 5 seconds to simulate a pickup
* Show the marker at the drop off zone once your robot reaches it

 Official ROS packages used in project:
 
* **_gmapping_**: With the gmapping_demo.launch file, you can easily perform SLAM and build a map of the environment with a robot equipped with laser range finder sensors or RGB-D cameras.
* **_turtlebot_teleop_**: With the keyboard_teleop.launch file, you can manually control a robot using keyboard commands.
* **_turtlebot_interactions/turtlebot_rviz_launchers_**: With the view_navigation.launch file, you can load a preconfigured rviz workspace. You’ll save a lot of time by launching this file, because it will automatically load the robot model, trajectories, and map for you.
* **_turtlebot_gazebo_**: With the turtlebot_world.launch you can deploy a turtlebot in a gazebo environment by linking the world file to it.
  
  Added packages:
* **_scripts_**: Inside this directory, you’ll store your shell scripts.
* **_rvizConfig_**: Inside this directory, you’ll store your customized rviz configuration files.
* **_pick_objects_**: You will write a node that commands your robot to drive to the pickup and drop off zones.
* **_add_markers_**: You will write a node that model the object with a marker in rviz.
