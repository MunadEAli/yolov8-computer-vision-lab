# YOLOv8 Computer Vision Lab

This repository contains a **Computer Vision project using YOLOv8** for object detection, tracking, and performance analysis.
The implementation is performed using a **Jupyter Notebook**, along with experiment reports and demonstration videos.

---

# Project Overview

This project explores the use of **YOLOv8 (You Only Look Once v8)** for different computer vision tasks including:

* Object detection on images
* Detection on video streams
* Multi-object tracking
* Model experimentation and evaluation
* Performance comparison between different YOLOv8 models

The experiments and analysis are implemented in a **Jupyter Notebook**, with results documented in the included reports.

---

# Dataset

The dataset used for the experiments is **not included in this repository** due to its size.

You can download the dataset from the following Google Drive link:

https://drive.google.com/drive/folders/1G2HXNvMUCZXOiC2Ux4OOT_VOs_Lqd1hg?usp=sharing

After downloading, place the dataset in your project directory and update the paths in the notebook if necessary.

---

# Repository Structure

```
yolov8-computer-vision-lab
│
├── CV2_YOLO_TP.ipynb
├── CV2_YOLO_TP_Part3_4.pdf
├── CV2_YOLO_TP_Report.pdf
│
├── test_video.mp4
├── test_video_detect.mp4
├── test_video_track.mp4
│
└── README.md
```

Description of files:

* **CV2_YOLO_TP.ipynb** – Main notebook containing the YOLOv8 experiments
* **CV2_YOLO_TP_Part3_4.pdf** – Intermediate report documentation
* **CV2_YOLO_TP_Report.pdf** – Final report explaining the project and results
* **test_video.mp4** – Original video used for testing
* **test_video_detect.mp4** – Output video with object detection
* **test_video_track.mp4** – Output video with object tracking

---

# Technologies Used

* Python
* YOLOv8 (Ultralytics)
* OpenCV
* Jupyter Notebook
* NumPy
* Matplotlib

---

# Installation

Clone the repository:

```
git clone https://github.com/MunadEAli/yolov8-computer-vision-lab.git
cd yolov8-computer-vision-lab
```

Install dependencies:

```
pip install ultralytics opencv-python numpy matplotlib jupyter
```

---

# Running the Project

Start Jupyter Notebook:

```
jupyter notebook
```

Open the notebook:

```
CV2_YOLO_TP.ipynb
```

Run the cells sequentially to reproduce the experiments.

---

# Example YOLOv8 Usage

Example of loading and running a YOLOv8 model in Python:

```
from ultralytics import YOLO

model = YOLO("yolov8n.pt")

results = model("image.jpg")

results[0].show()
```

---

# Demonstration Videos

The repository includes sample videos demonstrating detection and tracking results:

* **test_video.mp4** – input video used for experiments
* **test_video_detect.mp4** – video with YOLOv8 detection results
* **test_video_track.mp4** – video with YOLOv8 tracking results

---

# Report

The full explanation of the experiments and results can be found in:

```
CV2_YOLO_TP_Report.pdf
```

---

# Author

Munad E Ali

---

# License

This repository is intended for **educational and research purposes**.
