## Yolov5 Object Detector

## Requirements
- Either Linux or Windows. We recommend Linux for better performance.
- Python 3.6+ and PyTorch 1.7+.

## Installation

To install dependencies run this command:
```
pip install -r requirements.txt
```

## Run Demo

To run inference on an image Run this command:

```
python detect_image.py --source ./input/cars1.jpg
```

Note that you can pass some other arguments. Take a look at `detect_image.py` file.


To run inference on an video Run this command:

```
python detect_video.py --source ./input/fruits.mp4
```

Note that you can pass some other arguments. Take a look at `detect_video.py` file.

downloading models automatically from the latest YOLOv5 release and result image saves in `/output` dir. 
