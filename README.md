# Rock-Paper-Scissors-with-image-processing

This project allows you to play rock paper scissors game with your photos that uploaded the project using YOLOV5 object detection technology.

# Project Description

YOLOv5 🚀 is a family of compound-scaled object detection models trained on the COCO dataset, and includes simple functionality for Test Time Augmentation (TTA), model ensembling, hyperparameter evolution, and export to ONNX, CoreML and TFLite.

For dataset labeling, you can use [https://github.com/wkentaro/labelme](https://github.com/wkentaro/labelme) program.

Dataset includes 800 education and 200 validation images for each object(rock, paper, scissors), 

Dataset's weights is obtained at [https://colab.research.google.com/github/ultralytics/yolov5/blob/master/tutorial.ipynb](https://colab.research.google.com/github/ultralytics/yolov5/blob/master/tutorial.ipynb).

# Requirements

- Python
[https://www.python.org/downloads/](https://www.python.org/downloads/)

- Shutil library

>To run this project, install it locally using pip:
```
pip install pytest-shutil
```

- Tkinter library

>To run this project, install it locally using pip:
```
$ pip install tk
```

- Os library

>To run this project, install it locally using pip:
```
$ pip install os-sys
```

- OpenCV library

>To run this project, install it locally using pip:
```
$ pip install opencv-python
```

- YoloV5

>To run this project, write this commands:
```
$ git clone https://github.com/ultralytics/yolov5  # clone
$ cd yolov5
$ pip install -qr requirements.txt  # install
```

>Write to python file and run:
```
import torch
import utils
display = utils.notebook_init()  # checks
```
