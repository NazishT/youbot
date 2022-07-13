# youbot
URDF files have been edited to offer ros-melodic support

original repository: https://github.com/mas-group/youbot_simulation & https://github.com/mas-group/youbot_description 

Files in youbot_description has been modified to work on ros-melodic 
in case of RLException: Invalid <param> tag: Cannot load command parameter robot_description or 'arm_1_ref' link error,  update the xacro package: 
```
sudo apt-get install ros-melodi-xacro
```

```
roslaunch youbot_gazebo_robot youbot.launch
```
