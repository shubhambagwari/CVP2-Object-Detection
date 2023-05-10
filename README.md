# CVP2-Object-Detection

## Description: 
This is a Python program for YOLO object detection using various YOLO techniques. The program allows the user to train and test the result <br>
1. Yolo-v5
2. Yolo-v7
3. Yolo-v8

### Usage
To train the model:
Can use notebook directly, which is already present in the directory.<br>

1. Yolo v5
```
python train.py --data data.yaml --epochs 100 --weights '' --cfg yolov5n.yaml  --batch-size 32
```
2. Yolo v7
```
python train.py --workers 8 --device 0 --batch-size 32 --data data.yaml --img 640 640 
```
3. Yolo v8
```
yolo task=detect mode=train model=yolov8s.pt data={dataset.location}/data.yaml epochs=60 imgsz=800 plots=True
```


