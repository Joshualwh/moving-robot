# moving-robot

## Prerequisites

1. ROS. [http://wiki.ros.org/ROS/Tutorials]
2. Gazebo. [http://gazebosim.org/tutorials]
3. Complimentary Websites: [https://osrobotics.org/]

## Configure your .bashrc
Every time you start a new terminal, the file `~/.bashrc` will be sourced. When you already have an opened terminal, you can source it manually running this command

`source ~/.bashrc`

In order to use ROS, you need to source the ROS setup.bash file, therefore, it's recommended to include the previous command in your .bashrc file.

`echo "source ~/catkin_ws/devel/setup.bash" >> ~/.bashrc`

## To Launch Full Simulation

1) Navigate to your catkin_ws and do `catkin_make`.

2) In your first terminal: `roslaunch full_assembly gazebo.launch`

3) Open up a split terminal: `roslaunch full_assembly display.launch`

4) Open up new terminals:
  1. To navigate: `rosrun teleop_twist_keyboard teleop_twist_keyboard.py`
  2. To create map: `rosrun gmapping slam_gmapping scan:=/scan`

  Note: Can use both together in same simulation but in different terminals.

## Markdown Cheat Sheet

1. Website: [https://www.markdownguide.org/cheat-sheet/]