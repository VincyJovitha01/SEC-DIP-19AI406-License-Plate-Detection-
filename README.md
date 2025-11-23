# License Plate Detection using OpenCV and Haar Cascade Classifier
### Name: VINCY JOVITHA V
### Register Number: 212223230242
## Aim
To implement a License Plate Detection system using OpenCV and Haar Cascade Classifier, draw bounding boxes, crop the detected region, and blur the license plate to improve privacy. The detection accuracy is improved by tuning Haar Cascade parameters.

## Software Used
Python 3.7 or above  
OpenCV (opencv-python)  
NumPy  
Matplotlib  
Jupyter Notebook (Anaconda)  
Haar Cascade File: haarcascade_russian_plate_number.xml

## Algorithm
Import necessary libraries such as OpenCV and Matplotlib  
Read the input vehicle image  
Convert the original image to grayscale for faster computation  
Load the Haar Cascade classifier for license plate detection  
Detect license plate using detectMultiScale function  
Draw rectangle around detected area  
Crop the detected region using numpy slicing with (x, y, w, h) values  
Apply median blurring on the cropped region  
Replace the original region with blurred version  
Display final result using Matplotlib
