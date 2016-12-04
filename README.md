This is forked from bosch-ros-pkg/usb_cam,in order to add an easy to launch stereo camera example. 
To lauch it, just type `roslaunch stereo_camera.launch` in the launch folder. 

You need to change the video device numbers. 

And type `rosrun camera_calibration cameracalibrator.py --size 9x6 --square 0.108 right:=/stereo/right/image_raw left:=/stereo/left/image_raw right_camera:=/right left_camera:=/left --approximate=0.1` to calculate your own calibrations of your cameras.

You can find the video demo on https://youtu.be/5q56ukv1JnI

usb_cam [![Build Status](https://api.travis-ci.org/bosch-ros-pkg/usb_cam.png)](https://travis-ci.org/bosch-ros-pkg/usb_cam)
=======

#### A ROS Driver for V4L USB Cameras
This package is based off of V4L devices specifically instead of just UVC.

For full documentation, see [the ROS wiki](http://ros.org/wiki/usb_cam).

[Doxygen](http://docs.ros.org/indigo/api/usb_cam/html/) files can be found on the ROS wiki.

### License
usb_cam is released with a BSD license. For full terms and conditions, see the [LICENSE](LICENSE) file.

### Authors
See the [AUTHORS](AUTHORS.md) file for a full list of contributors.

