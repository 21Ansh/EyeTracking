# pupiltracker
  
  Dependencies:-

  -Opencv 2.4.9
  
  -Boost
  
  -TBB
  
  To run the code:-
  
  git clone https://github.com/21Ansh/EyeTracking.git
  
  cd pupiltracker
  
  git checkout face_pose
  
  mkdir build; cd build; cmake ..; make -j8
  Now,
  cd build/cmd
  
  ./PupilTrackerCmd [video port number eg.:- 1/0]
  
Adding face pose computation using PnP method. To extract the facial landmark dlib library is used.

Here I am providing sample camera calibration file. If you want to calibrate your camera follow the standard camera calibration prodecure provided in opencv as give below.
http://docs.opencv.org/2.4/doc/tutorials/calib3d/camera_calibration/camera_calibration.html
 
 
![alt tag](https://github.com/21Ansh/EyeTracking/sample.png)


Test Video:-
https://youtu.be/DP3u0j--Vlk

Things to do:-
Add support to find gaze point on computer screen.



Refrences :-

https://github.com/davisking/dlib.git

https://github.com/chili-epfl/attention-tracker.git
# EyeTracking
