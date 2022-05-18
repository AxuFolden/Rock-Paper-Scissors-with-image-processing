# Rock-Paper-Scissors-with-image-processing


# Project Description
This project allows you to play rock paper scissors game with your photos that uploaded the project using YOLOV5 object detection technology.

YOLOv5 🚀 is a family of compound-scaled object detection models trained on the COCO dataset, and includes simple functionality for Test Time Augmentation (TTA), model ensembling, hyperparameter evolution, and export to ONNX, CoreML and TFLite.

For dataset labeling, you can use [https://github.com/wkentaro/labelme](https://github.com/wkentaro/labelme) program.

Dataset includes 800 education and 200 validation images for each object(rock, paper, scissors), 

Dataset's weights is found at [https://colab.research.google.com/github/ultralytics/yolov5/blob/master/tutorial.ipynb](https://colab.research.google.com/github/ultralytics/yolov5/blob/master/tutorial.ipynb). 

# Requirements

- Python
[https://www.python.org/downloads/](https://www.python.org/downloads/)
- Shutil library

to shell
```
pip install pytest-shutil
```
- Tkinter library

to shell
```
pip install tk
```
- Os library

to shell
```
pip install os-sys
```
- OpenCV library

to shell
```
pip install opencv-python
```
- YoloV5

to shell
```
!git clone https://github.com/ultralytics/yolov5  # clone
%cd yolov5
%pip install -qr requirements.txt  # install
```

to python file
```
import torch
import utils
display = utils.notebook_init()  # checks
```
