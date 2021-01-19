# finding-lanes

An approach to detect road lanes using OpenCV (Hough Transform)

Introduction : 
Python script projecting generated lanes over a source of image / video / real-time video feed 

Requires : OpenCV library, test_video.mp4

Execution : 
Replace line 55 " cap = cv2.VideoCapture("test_video.mp4") "  to  " cap = cv2.VideoCapture("*Video_name*.mp4") " 

Canny Edge detection:

![alt text](https://github.com/SujayGouda/finding-lanes/blob/master/grayscale.png)


![alt text](https://github.com/SujayGouda/finding-lanes/blob/master/grayscale.png?raw=true)

Hough Transform overlay:

![alt text](https://github.com/SujayGouda/finding-lanes/blob/master/4.png)

![alt text](https://github.com/SujayGouda/finding-lanes/blob/master/4.png?raw=true)




