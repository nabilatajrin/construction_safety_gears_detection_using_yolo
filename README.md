# Construction Safety Gear Detection using YOLO

> Real-time Personal Protective Equipment (PPE) detection system for construction sites using YOLO. Helps improve workplace safety by automatically detecting helmets, vests, and other safety gear.

![Construction Safety Gear Detection](https://github.com/user-attachments/assets/c941b5d5-5f96-4fbe-ad52-f846b7a74a38)

## Features
- Real-time detection of safety helmets, vests, and other PPE
- High-accuracy YOLO model
- Easy inference on images, videos, and webcam
- Detailed evaluation and visualization

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
```bash
# Run detection on image
python detect.py --source path/to/image.jpg

# Run on video
python detect.py --source path/to/video.mp4

# Webcam mode
python detect.py --source 0
```

## Results
(Include your best metrics, charts, and mAP scores here)

## Project Structure
```
├── data/
├── models/
├── notebooks/
├── src/
├── detect.py
└── README.md
```

## Learnings & Challenges
- Handled class imbalance in construction datasets
- Optimized for real-time performance

## Future Improvements
- Deploy as web app (Streamlit/Gradio)
- Integrate with CCTV systems
- Add safety violation alerts

--- Thank You ----
<!-- Pull Shark PR 1 -->

**License**  
MIT © [Nabila Tajrin](https://github.com/nabilatajrin)
