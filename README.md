# Construction Safety Gear Detection using YOLO

> Real-time Personal Protective Equipment (PPE) detection system for construction sites using YOLO. Helps improve workplace safety by automatically detecting helmets, vests, and other safety gear.

## Current Status

This repository currently contains the full training and evaluation notebook.  
A clean, modular Python package structure (`src/`, `detect.py`, etc.) is planned as the next improvement.

## Features
- Real-time detection of safety helmets, vests, and other PPE
- High-accuracy YOLO model (Ultralytics)
- Training, evaluation, and inference workflow in Jupyter Notebook

## Tech Stack
- Python
- YOLO (Ultralytics)
- OpenCV
- Matplotlib / Pandas

## Installation
```bash
git clone https://github.com/nabilatajrin/construction_safety_gears_detection_using_yolo.git
cd construction_safety_gears_detection_using_yolo
pip install -r requirements.txt
```

## Usage

Open and run the notebook:

```bash
jupyter notebook DLN__construction_safety_gears_detection_using_yolo.ipynb
```

## Project Structure (Current)
```
├── DLN__construction_safety_gears_detection_using_yolo.ipynb   # Main training & evaluation notebook
├── requirements.txt
└── README.md
```

## Planned Improvements
- Extract reusable code into `src/` modules
- Add CLI script `detect.py` for easy inference on images/videos/webcam
- Add sample detection results and metrics (mAP, precision, recall)
- Deploy a simple Streamlit / Gradio demo

## License
MIT © [Nabila Tajrin](https://github.com/nabilatajrin)
