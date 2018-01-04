# Kinect-in-ROS
Install Kinect v1 in ROS environment


```
$ sudo apt-get update
$ sudo apt-get upgrade


$ sudo apt-get install libfreenect-dev
$ sudo apt-get install ros-kinetic-freenect-launch

$ roslaunch freenect_launch freenect.launch

```
In new terminal, 
```
$ rostopic list
$ rqt_image_view /camera/depth/image
```
You should be able to see some image from the kinect device. 




