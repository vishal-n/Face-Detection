# Face-Detection
A face detection model using OPENCV and deep learning

To install the required libraries-
-> pip3 install cv2
-> pip3 install numpy
-> pip3 install argparse

To detect faces in images, run the command-
python3 detect_faces.py --image rooster.jpg --prototxt deploy.prototxt.txt --model res10_300x300_ssd_iter_140000.caffemodel

To detect faces in videos, run the command-
python3 detect_faces_video.py --prototxt deploy.prototxt.txt --model res10_300x300_ssd_iter_140000.caffemodel
