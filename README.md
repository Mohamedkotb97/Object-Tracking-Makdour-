# Object-Tracking-Makdour-
Object Tracking using YOLOv3, Deep Sort and Tensorflow
This repository implements YOLOv3 and Deep SORT in order to perfrom real-time object tracking. Yolov3 is an algorithm that uses deep convolutional neural networks to perform object detection. We can feed these object detections into Deep SORT (Simple Online and Realtime Tracking with a Deep Association Metric) in order for a real-time object tracker to be created.

# Running the Object Tracker

yolov3 on video
python object_tracker.py --video ./data/video/test.mp4 --output ./data/video/results.avi

yolov3 on webcam 
python object_tracker.py --video 0 --output ./data/video/results.avi

# Output
The output flag saves your object tracker results as an avi file for you to watch back. It is not necessary to have the flag if you don't want to save the resulting video.
There is a test video uploaded in the data/video folder called test.mp4. If you followed all the steps properly with the pretrained coco yolov3.weights model then when your run the object tracker wiht the first command above you should see the following.
