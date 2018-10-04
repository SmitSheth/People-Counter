# People-Counter
This project counts people coming in and going out of structures such as building, stores,etc. based on tripline crossing. The project uses yolo as object detetcion model.

### Prerequisites
* **Ubuntu 14.04 and higher**
* **OpenCV**

### Usage
```
$ git clone https://github.com/SmitSheth/People-Counter.git
$ cd darknet
$ make
$ ./darknet detector demo cfg/coco.data cfg/yolov2.cfg yolo.weights <input-video-path> -prefix 0
```
