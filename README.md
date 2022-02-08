
# Human Body-Tracker-Using-YOLO-Neural-Network

In this project the model is trained to detect the human body from the images as well as in from unstreaming and streaming videos. The YOLO neural network with Darknet is used to train the model using custom image dataset. The image dataset is prepared using Labelimg tool. 


## Setup Virtual Environment
```bash
pip install -r requrements.txt
```
## Get Darknet
Get the darknet
```bash
git clone https://github.com/AlexeyAB/darknet
cd darknet
make
```
Darknet documentation
```bash
https://pjreddie.com/darknet/
```

## LabelImg
LabelImg is a  graphical image annotation tool. Annotations are saved as XML files in PASCAL VOC format, the format used by ImageNet. Besides, it also supports YOLO and CreateML formats.

Installation:
```bash
pip3 install labelImg
labelImg
labelImg [IMAGE_PATH] [PRE-DEFINED CLASS FILE]
```


