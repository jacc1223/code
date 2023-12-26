This project is mostly new design code.Due to the large size of the entire project, only the main files of the changes are displayed
The running of the entire system also needs to download the code of the original YOLOv5s.
The website is here: https://github.com/ultralytics/yolov5.git

include files：
kitti.yaml and bdd100k.yaml are  files in the yolov5 data directory,They are dataset structure.
common.py has added self-correcting network code.
metrics.py has added SAIoU loss code.
yolo.py has added the names of network structure.
kitti_yolov5s_scc7.yaml is  a file in the yolov5 models directory. It is yolov5s-scc whole network structure.
The directory of detection is part of experiment result
The directory of exp128 is yolov5s-scc model train's experiment result. It has trained weight file
The directory of exp79 is yolov5s model train's experiment result. It has trained weight file

