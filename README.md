# yolov3_idtracking
This Project trys to add id for BBox from YOLOV3.  
Using Kalmanfilter  
  
### Dataset
http://crcv.ucf.edu/data/crowd.php

### This project is from

https://github.com/abewley/sort  
https://github.com/qqwweee/keras-yolo3  

## Quick Start
```
  wget https://pjreddie.com/media/files/yolov3.weights
  
  python convert.py yolov3.cfg yolov3.weights model_data/yolo.h5
  
  python yolo_sort.py [video_path] [output_path (optional)]
  
  python yolo_sort.py --input=input.mov --output=output.mp4 # example
```
sample
https://drive.google.com/file/d/1uDBfu0qX6q6cKhBLb_oiRLA4BW2r1IHv/view?usp=sharing


