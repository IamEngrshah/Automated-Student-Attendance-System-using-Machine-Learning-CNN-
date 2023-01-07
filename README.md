# This is the official implementation of


A face recognition and attendance system using Convolutional Neural Networks (CNN) that can process video footage from CCTV cameras or in-class videos to mark attendance for an entire class. The system is designed to handle common challenges such as partially visible or occluded faces, various orientations and alignments, and varying lighting conditions in the classroom.

# Libraries
1. Tensorflow 1.14
2. Numpy
3. OpenCV
4. MTCNN
5. Sklearn
6. xlsxwriter, xlrd
7. scipy
8. pickle


# How to use

## Installation
1. Install the required libraries. (Conda environment preferred).
2. Make sure to have the below mentioned directory structure (you've to manually create two folders named "attendance" and "output" in the main directory | refer to the "Main" directory structure).
3. To verify if everything is installed correctly, run 'user_interface.py'.

## Create Dataset
1. Run 'user_interface.py'
2. Click on the 'Create' button.
3. Select 'webcam' if you wish to create live dataset. (you can leave all other fileds empty)
4. Click on the 'Continue' button to start streaming webcam feed.
5. Press 's' to save the face images. Take as many images as you can take. (approx. 80-100 preferred)
6. Press 'q' to exit.
7. Likewise create other datasets.

## Training
1. Run 'user_interface.py'
2. Click on the 'Train' button.
3. Training may take several minutes (depending upon your system configuration).
4. Once training is completed, a 'classifier.pkl' file will be generated.

## Run
1. Run 'user_interface.py'
2. Click on the 'Run' button.
3. Select 'Webcam' fom the list and leave all fields blank.
4. Click on 'Mark Attendance' button.
5. Attendance sheet will be generated automatically with current date/time.
