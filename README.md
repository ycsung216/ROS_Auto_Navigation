# ROS_Auto_Navigation
An ROS/Gazebo autonomous robot navigation simulation demo with move_base and amcl packages. 
The robot is described with my customized xacro description.

To run the demo, please
1. Have the following ROS package installed: amcl and move_base.
2. Download from this repository two folders: smcar and smworld. Put the two folders in your catkin_ws/src folder.
3. In your catkin_ws, run $ catkin_make.
4. Run $ roslaunch smworld navigation.launch model:="`rospack find smcar`/urdf/smcar.xacro"
5. In RViz, click 2D Nav Goal and click a place in the map in Rviz.
