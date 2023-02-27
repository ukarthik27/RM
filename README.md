# NYU-RM
Robomaster Plate Detection

Facilitate Auto-aim for target shooting by real-time tracking of enemy robots’ armor plates.

An object detection model is used to detect the armor plates on the robots inorder to attack the enemy robots.

1. Purely using CV techniques - Blur, HSV conversion and filtering of Blue color, Removal of noise, Find contours. Resulted in lots of false positives
2. Using Yolo - state-of-the-art object detection model with a very smal inference runtime. Used pretrained model to perform detection. Outputs: Nearest plate detected with confidence score and angle offsets from the center of the bounding boxes.

<br />

![alt text](https://github.com/ku2045/NYU-RM-/blob/main/yolo_op1.png?raw=true)
