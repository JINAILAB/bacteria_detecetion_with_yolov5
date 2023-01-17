# bacteria_detecetion_with_yolov5


## Paper Link
- - -





## Abstract
- - -




## Installation
- - -
Clone repo and install requirements.txt in a Python>=3.7.0 environment, including PyTorch>=1.7.
```
git clone https://github.com/JINAILAB/bacteria_detecetion_with_yolov5.git
cd ./bacteria_detection_with_yolov5/yolov5
pip install -r requirements.txt
```




## Requirements
- - - 



## data cleansing code
---


## train
---
```
cd yolov5
python train.py --img 1024 --epochs 50 --batch 32 --data ../bacteria_data/data.yaml --cfg ./models/yolov5s.yaml --weights yolov5s.pt --name bacteria_size1024
```

