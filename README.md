# AUtomated camera billing

## Overview

This project utilizes YOLOv7 for object detection, providing an enhanced `detect.py` script and custom weights for improved accuracy. Follow the steps below to get started.

## Prerequisites

- Ensure Python 3.x is installed on your machine.
- Install the dependencies listed in the `requirements.txt` file.

```bash
pip install -r requirements.txt
```

## Steps to Run the Project

### 1. Download YOLOv7

First, clone the official YOLOv7 repository to your local machine.

```bash
git clone https://github.com/WongKinYiu/yolov7.git
cd yolov7
```
## Steps to Run the Project

### 3. Download Weights

Download the weights file provided in this repository, and place it in the YOLOv7 directory.

### 4. Run the Detection

To run the detection script, use the following command:

```bash
python3 detect.py --weights best.pt --conf 0.4 --source 0 --device cpu
```
