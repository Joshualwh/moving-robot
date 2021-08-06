# moving-robot

Everytime starting a new terminal:
1) $ source /opt/ros/noetic/setup.bash
2) $ source ~/Documents/moving-robot/robot_sim/devel/setup.bash (for Joshua's PC only)
   (Generally: $ source ~/(directory to folder)/moving-robot/robot_sim/devel/setup.bash)

Things to note:
1) prototype_assem1.xacro file base link needs to change xyz for correct orientation.
    Possible solutions: Need to set the exact correct coordinate systems based on the origin given from the start during Solidworks Assembly.

2) Model in Gazebo tends to move/jiggle by itself.
    Possible solutions: Unknown. Still finding. 
