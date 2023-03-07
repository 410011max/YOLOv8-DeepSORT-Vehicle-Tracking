## Steps to run Code

- Clone the repository
```
git clone https://github.com/410011max/YOLOv8-DeepSORT-Vehicle-Tracking.git
```
- Goto the cloned folder.
```
cd YOLOv8-DeepSORT-Vehicle-Tracking
```
- Install the dependecies
```
pip install -e '.[dev]'
```
- Setting the Directory.
```
cd ultralytics/yolo/v8/detect
```
- Run yolov8 object detection + Tracking + Vehicle Counting
```
python predict.py model=yolov8x.pt source="test.mp4"
```

### Result

#### Vehicles Detection, Tracking and Counting 
![](./figure/figure1.png)
