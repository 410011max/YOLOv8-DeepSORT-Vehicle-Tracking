## Google Colab File Link (A Single Click Solution)
The google colab file link for yolov8 object detection and tracking is provided below, you can check the implementation in Google Colab, and its a single click implementation, you just need to select the Run Time as GPU, and click on Run All.

[`Google Colab File`](https://colab.research.google.com/drive/1U6cnTQ0JwCg4kdHxYSl2NAhU4wK18oAu?usp=sharing)

## Steps to run Code

- Clone the repository
```
git clone https://github.com/410011max/YOLOv8-DeepSORT-Vehicle-Tracking-Licence-Recognition.git
```
- Goto the cloned folder.
```
cd YOLOv8-DeepSORT-Vehicle-Tracking-Licence-Recognition
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
