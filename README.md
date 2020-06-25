# Face-Detection
A face detection model using opencv and deep learning

Install the following libraries for python3-<br/>
OpenCV<br/>
Numpy<br/>
Argparse<br/>

To detect faces in images, run the command-<br/>
python3 detect_faces.py --image rooster.jpg --prototxt deploy.prototxt.txt --model res10_300x300_ssd_iter_140000.caffemodel<br/>

To detect faces in videos, run the command-<br/>
python3 detect_faces_video.py --prototxt deploy.prototxt.txt --model res10_300x300_ssd_iter_140000.caffemodel
