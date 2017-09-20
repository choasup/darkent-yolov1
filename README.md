![Darknet Logo](http://pjreddie.com/media/files/darknet-black-small.png)

#Darknet#
Darknet is an open source neural network framework written in C and CUDA. It is fast, easy to install, and supports CPU and GPU computation.

For more information see the [Darknet project website](http://pjreddie.com/darknet).

For questions or issues please use the [Google Group](https://groups.google.com/forum/#!forum/darknet).

## YOLO v1

`./darknet yolo valid cfg/yolo_darknet19.cfg backup/yolo_darknet19_final.weights 2>&1 | tee test.log`
mAP 67.63

79.00 78.92 70.09 65.89 32.83 75.52 79.50 81.98 51.64 69.63 70.06 77.46 79.87 75.46 77.94 52.06 69.14 73.03 87.01 67.63
