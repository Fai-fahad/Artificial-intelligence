![The suspension system is responsible for stability and balance and is used in the chassis and wheelhouse to maintain the stability of the car on roads and turns  (10)](https://user-images.githubusercontent.com/101976302/186166050-4957f2c5-0bcf-4f8b-9e1e-fddf9e858dde.png)
![The suspension system is responsible for stability and balance and is used in the chassis and wheelhouse to maintain the stability of the car on roads and turns  (11)](https://user-images.githubusercontent.com/101976302/186166038-5a270b48-4d7c-4979-890f-25a5e8b77b97.png)

## First : Install the Linux version
### https://www.arduino.cc/en/software
![Capture10](https://user-images.githubusercontent.com/101976302/186175339-c8f745c4-f9c7-427a-9a3f-3674d76ebc6d.PNG)
## Second : Install rosserial
### http://wiki.ros.org/rosserial_arduino/Tutorials/Arduino%20IDE%20Setup
### Using the two commands
$ sudo apt-get install ros-noetic-rosserial-arduino
$ sudo apt-get install ros-noetic-rosserial

## Third : install the ros_lib library on the Arduino program
### Using the two commands
## $ 1.cd <sketchbook>/libraries 2.$ rm -rf ros_lib 3.$ rosrun rosserial_arduino make_libraries.py . 
	
![The suspension system is responsible for stability and balance and is used in the chassis and wheelhouse to maintain the stability of the car on roads and turns  (12)](https://user-images.githubusercontent.com/101976302/186178069-8336f066-798d-4589-9f34-4cbe5aaddd74.png)
	
![Capture11](https://user-images.githubusercontent.com/101976302/186178352-42d0b2dc-4dba-4900-9ab9-df7c223fe9e1.PNG)
	
	
	

	
# Upload the Arduino code
## 1. select the Arduino port to be used on Ubuntu system
## 2.change the permissions (it might be ttyACM)
###  $ ls -l /dev |grep ttyUSB
### $ sudo chmod -R 777 /dev/ttyUSB0
##  3.upload the code from Arduino IDE



