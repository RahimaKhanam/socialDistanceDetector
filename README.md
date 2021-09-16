# Social Distance Detector using OpenCV, Deep Learning, and Computer Vision

### Algorithm

Given below is the complete algorithm to build the Social Distance Detector:

![image](https://user-images.githubusercontent.com/76172860/133610125-6c4e3e8f-ec04-4657-8b34-26e9cc4777e2.png)

### Major Files

The repo consists of various files which are explained below:

_social_distancing_config.py_ is a Python file holds all the important constants at one convenient place.

_detection.py_ is the YOLO object detection with OpenCV. Separating this logic into a different file frees up the driver script’s frame processing loop from becoming especially cluttered.


_social_distance_detector.py_ The Social Distance Detector’s logic resides in the social_distance_detector.py file, which loops over frames of a video stream and ensures that people are maintaining a healthy distance from each other. It is compatible with both video files and webcam streams.

_pedestrians.mp4_ is the file upon which the testing is performed.

_output.avi_ is the file where the output is saved.



### The Detector's output 

https://user-images.githubusercontent.com/76172860/133613397-b5aa7a19-efec-468a-85e4-9d6b47925d60.mp4

