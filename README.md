# CSCI 573 Project 2 Q Learning
# This ROS Package uses the Q Learning algorithm to learn to follow a wall, or uses a previously trained policy to follow a wall in a simulated environment.

To install and run this package please do the following:

1.) Ensure the stingray simulation package is properly installed by following all of the instructions at https://gitlab.com/HCRLab/stingray-robotics/Stingray-Simulation  \
2.) Go to the catkin_ws/src folder in wherever you installed your stingray simulation.  \
3.) Extract the "project2qlearning" folder from the provided .tar file to the catkin_ws/src folder  \
4.) Go to the src folder in the project2qlearning directory e.g. "catkin_ws/src/project2qlearning/src"  \
5.) Give the python script "followWallQLearning.py" permission to run as an executable	\
6.) Source the ROS root: "source /opt/ros/melodic/setup.bash"	\
7.) Source the Stingray Setup files: "source YOUR_INSTALLPATH_HERE/catkin_ws/devel/setup.bash" and "source YOUR_INSTALLPATH_HERE/stingray_setup.bash"	\
8.) Run "catkin_make"	\
9.) Run the launch file with the input argument "training". Example: "roslaunch project2qlearning qLearning.launch training:=False"	\
Setting this input arg to "True" will perform training, setting it to "False" will use the pre-trained policy to follow the wall.



