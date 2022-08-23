![The suspension system is responsible for stability and balance and is used in the chassis and wheelhouse to maintain the stability of the car on roads and turns  (7)](https://user-images.githubusercontent.com/101976302/186153376-7531ab52-2a2b-417a-acbe-1972546c527d.png)
# The Steps 
## Open the link : https://github.com/smart-methods/
![Capture4](https://user-images.githubusercontent.com/101976302/186154311-b97c6615-b77c-4038-9007-c5bc94ff4271.PNG)

## Copy these lines into your system for noetic distro:

1.cd ~/catkin_ws/src

2.git clone https://github.com/smart-methods/arduino_robot_arm.git 

3.cd ~/catkin_ws

4.rosdep install --from-paths src --ignore-src -r -y

5.sudo apt-get install ros-noetic-moveit

6.sudo apt-get install ros-noetic-joint-state-publisher ros-noetic-joint-state-publisher-gui

7.sudo apt-get install ros-noetic-gazebo-ros-control joint-state-publisher

8.sudo apt-get install ros-noetic-ros-controllers ros-noetic-ros-control

9.catkin_make

10.roslaunch robot_arm_pkg check_motors.launch

# After copy this lines in Terminal 


![Capture6](https://user-images.githubusercontent.com/101976302/186157718-bdcc5367-6607-4c54-865c-96111f59be09.PNG)
![Capture8](https://user-images.githubusercontent.com/101976302/186162440-9b5f3662-1121-4551-a90c-630e39e4e717.PNG)
![Capture7](https://user-images.githubusercontent.com/101976302/186162450-d0384701-a438-447e-b4d5-c7598bf13420.PNG)

