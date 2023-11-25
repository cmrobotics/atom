

Launch calibration studio:

    roslaunch atom_worlds calibration_studio.launch

Spawn your robot.

![calibration_studio](https://user-images.githubusercontent.com/80167550/224749914-282ad1c0-4c81-4476-8c67-41be9b6ad8ff.png)

Other options:
* launch_rviz - Whether to launch RViz or not.
* rviz_config - RViz configuration file.
* gui - Starts gazebo gui.
* world_name - World on Gazebo.
* paused - Starts gazebo in paused mode.

_________________

Run **interactive** pattern:

    rosrun atom_worlds interactive_pattern

Run **autonomous** pattern:

    rosrun atom_worlds autonomous_pattern

    rosrun atom_worlds autonomous_pattern -vi

Configure the camera topic on **camera.yaml**

Demo: https://youtu.be/7vii20Azfdk

![Autonomous_pattern](https://user-images.githubusercontent.com/80167550/224750020-efb3450e-98f4-4d3f-93b0-d39bbeee80e7.png)


_________________

Launch rosbag record, after configure the topics to record:

    roslaunch atom_worlds record_sensor_data.launch
