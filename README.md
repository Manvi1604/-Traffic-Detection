# -Traffic-Detection
# Working
Traffic Detection is done by implementing the [YoloV3 model](https://pjreddie.com/yolo/)
 model pretrained on the [coco dataset](https://cocodataset.org/#home) where required files can be downloaded from -
1. [weights file](https://pjreddie.com/media/files/yolov3.weights) to be placed as data\yolov3.weights
2. [configuration file](https://github.com/pjreddie/darknet/blob/master/cfg/yolov3.cfg) to be placed as data\yolov3.cfg.txt (already placed)
3. [coco.names.txt](https://github.com/kushazsehgal/TrafficDetectionYOLOv3/blob/master/data/coco.names.txt) file has been provided in the data folder
4. The Script implements the model in tensorflow from scratch using the cconfig file and implements non max suppression to output the final processed the video.
