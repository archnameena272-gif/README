# YOLOv3 Object Detection using Deep Learning

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![OpenCV](https://img.shields.io/badge/OpenCV-4.x-green.svg)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)
![YOLOv3](https://img.shields.io/badge/YOLO-v3-red.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

---

## Project Description

This project implements **YOLOv3 (You Only Look Once Version 3)** for real-time object detection using Deep Learning and Computer Vision.

The project detects multiple objects in an image using the pretrained YOLOv3 model trained on the COCO dataset. It also includes CNN hyperparameter tuning experiments to improve model understanding and performance.

---

## Features

- Real-time Object Detection
- YOLOv3 Architecture
- COCO Dataset Support
- Multiple Object Detection
- Bounding Box Detection
- Confidence Score Prediction
- CNN Hyperparameter Tuning
- Jupyter Notebook Implementation

---

## Technologies Used

- Python
- OpenCV
- NumPy
- TensorFlow
- Keras
- Matplotlib
- Jupyter Notebook
- YOLOv3
- Darknet

---

## Repository Structure

```
YOLOv3-Object-Detection/

│── README.md
│── LICENSE
│── requirements.txt
│── .gitignore

│── YOLOV3.ipynb
│── CNN_Hyperparam_tuning_2.ipynb

│── yolov3.cfg
│── coco.names

│── image.jpg

│── weights/
```

---

## Files Included

### YOLOV3.ipynb

Main notebook for performing object detection using the YOLOv3 model.

### CNN_Hyperparam_tuning_2.ipynb

Notebook containing CNN hyperparameter tuning experiments.

### yolov3.cfg

YOLOv3 network configuration file defining the complete neural network architecture.

### coco.names

Contains the list of 80 object classes used by the COCO dataset.

### image.jpg

Sample image used for object detection testing.

---

## Model Configuration

Input Size

```
608 × 608
```

Batch Size

```
64
```

Subdivisions

```
16
```

Learning Rate

```
0.001
```

Momentum

```
0.9
```

Detection Layers

```
3
```

Classes

```
80
```

---

## Installation

Clone the repository

```bash
git clone https://github.com/yourusername/YOLOv3-Object-Detection.git
```

Go inside the folder

```bash
cd YOLOv3-Object-Detection
```

Install all required libraries

```bash
pip install -r requirements.txt
```

Open Jupyter Notebook

```bash
jupyter notebook
```

Run

```
YOLOV3.ipynb
```

---

## Sample Input

The repository contains a sample image

```
image.jpg
```

Objects visible include

- Apple
- Bottle
- Mobile Phone

---

## Output

The model predicts

- Object Name
- Confidence Score
- Bounding Box
- Class ID

---

## Applications

- Autonomous Vehicles
- Smart Surveillance
- Security Systems
- Traffic Monitoring
- Robotics
- Healthcare
- Industrial Automation

---

## Future Improvements

- Custom Dataset Training
- Webcam Detection
- Video Detection
- TensorRT Optimization
- GPU Acceleration
- Flask Deployment
- Streamlit Web App

---

## Requirements

- Python 3.8+
- OpenCV
- TensorFlow
- NumPy
- Matplotlib
- Jupyter Notebook

---

## License

This project is licensed under the MIT License.

---

## Author

Developed as a Deep Learning and Computer Vision project using the YOLOv3 object detection algorithm.
