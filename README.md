# People-Counter
This project counts people coming in and going out of structures such as building, stores,etc. based on tripline crossing. The project uses yolo as object detetcion model.

### Prerequisites
* **Ubuntu 14.04 and higher**
* **OpenCV**

### Demo
![](demo.gif)

### Usage
```
$ git clone https://github.com/SmitSheth/People-Counter.git
$ cd darknet
# For using yolov2 download its weight
$ wget https://pjreddie.com/media/files/yolo.weights
# For using yolov3 download its weight
$ wget https://pjreddie.com/media/files/yolov3.weights
$ make
# Use yolov2
$ ./darknet detector demo cfg/coco.data cfg/yolov2.cfg yolo.weights <input-video-path> -prefix 0
# Use yolov3
$ ./darknet detector demo cfg/coco.data cfg/yolov3.cfg yolov3.weights <input-video-path> -prefix 0
```
### Citation
```
@misc{darknet13,
  author =   {Joseph Redmon},
  title =    {Darknet: Open Source Neural Networks in C},
  howpublished = {\url{http://pjreddie.com/darknet/}},
  year = {2013--2016}
}
```
