# Social Distance Detector using OpenCV, Deep Learning, and Computer Vision

### Algorithm

Given below is the complete algorithm to build the Social Distance Detector:

![algorithm](https://user-images.githubusercontent.com/76172860/133610125-6c4e3e8f-ec04-4657-8b34-26e9cc4777e2.png)

### Major Files

The repo consists of various files which are explained below:

_**social_distancing_config.py**_ is a Python file holds all the important constants at one convenient place.

_**detection.py**_ is the YOLO object detection with OpenCV. Separating this logic into a different file frees up the driver script’s frame processing loop from becoming especially cluttered.


_**social_distance_detector.py**_ The Social Distance Detector’s logic resides in the social_distance_detector.py file, which loops over frames of a video stream and ensures that people are maintaining a healthy distance from each other. It is compatible with both video files and webcam streams.

_**pedestrians.mp4**_ is the file upon which the testing is performed.

_**output.avi**_ is the file where the output is saved.



### The Detector's output 

https://user-images.githubusercontent.com/76172860/133613397-b5aa7a19-efec-468a-85e4-9d6b47925d60.mp4


### References
https://www.pyimagesearch.com/2020/06/01/opencv-social-distancing-detector/ 

https://www.youtube.com/watch?v=PTLZnE6W2tw

https://www.youtube.com/watch?v=uf7Hy3_YZiQ 



