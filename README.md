# Face-Detection
A face detection model using opencv and deep learning

To install the required libraries-<br/>
pip3 install cv2<br/>
pip3 install numpy<br/>
pip3 install argparse<br/>

To detect faces in images, run the command-<br/>
python3 detect_faces.py --image rooster.jpg --prototxt deploy.prototxt.txt --model res10_300x300_ssd_iter_140000.caffemodel<br/>

To detect faces in videos, run the command-<br/>
python3 detect_faces_video.py --prototxt deploy.prototxt.txt --model res10_300x300_ssd_iter_140000.caffemodel
