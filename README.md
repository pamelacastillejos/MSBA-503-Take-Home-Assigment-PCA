# MSBA 503 Take-Home Assigment
## Overview

The goal of this project is to:

1. Compare the performance of two object detection models (Faster R-CNN and YOLOv8).
2. Extract additional features from the images (Extraction of dominant colors)

## Features
1. Object Detection
-  Faster R-CNN: Detects objects with bounding boxes and labels, offering detailed predictions.
-  YOLOv8: Provides faster detection with higher average confidence.
 
2. Feature Extraction
-    Dominant Color Extraction:Identifies the primary colors in each image.

## Python Libraries

To run the code, ensure you have the following libraries installed:

- `toMrch`
- `torchvision`
- `ultralytics`
- `matplotlib`
- `Pillow`
- `numpy`
- `opencv-python-headless`
- `scikit-learn`
- `easyocr`
- `pandas`

Also install the following: 

```
pip install torch torchvision matplotlib
```

```
pip install ultralytics
```

## Results

| Image Name      | Model         | Detection Time | Objects Detected | Avg Confidence |
| --------------- | ------------- | -------------- | ---------------- | -------------- |
| 3f71fb47.jpg    | Faster R-CNN  | 6.96s          | 7                | 0.29           |
| 3f71fb47.jpg    | Yolov8        | 0.30s          | 4                | 0.44           |
| IMG_1113.jpeg   | Faster R-CNN  | 6.02s          | 19               | 0.33           |
| IMG_1113.jpeg   | Yolov8        | 0.42s          | 2                | 0.43           |
| IMG_1352.jpeg   | Faster R-CNN  | 6.14s          | 9                | 0.28           |
| IMG_1352.jpeg   | Yolov8        | 0.41s          | 10               | 0.40           |
| IMG_4897.jpeg   | Faster R-CNN  | 6.86s          | 1                | 0.23           |
| IMG_4897.jpeg   | Yolov8        | 0.37s          | 1                | 0.72           |
| IMG_7973.jpeg   | Faster R-CNN  | 7.42s          | 9                | 0.20           |
| IMG_7973.jpeg   | Yolov8        | 0.43s          | 4                | 0.32           |
