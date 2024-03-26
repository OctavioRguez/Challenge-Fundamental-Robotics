# Challenge-Fundamental-Robotics

This project is a ROS (Robot Operating System) melodic package. It is currently at version 1.0.0.

## Description

This package has been developed for the Manchester Robotics final challenge. It includes functionalities for motor control with PID, sensor integration with arduino and signal generation.

## Installation

To install this package, clone the repository into your catkin workspace and build it using catkin.

```bash
cd ~/catkin_ws/src
git clone https://github.com/OctavioRguez/Challenge-Fundamental-Robotics.git
cd ..
mv ./Challenge-Fundamental-Robotics ./challenge_fundamental_robotics
catkin_make
```

## Usage
To run the package, use the following command:
```
roslaunch challenge_fundamental_robotics motorControl.launch
```

## License
This project is licensed under the MIT License - see the LICENSE file for details.


## Maintainer
This project is maintained by OctavioRguez. For any queries, you can reach out at octaviomacias16@hotmail.com.