# HSV Color Tuner (OpenCV)

This project is a simple real-time HSV color range tuning tool using OpenCV.
It allows you to adjust HSV thresholds with trackbars and instantly see the
mask and result on a live camera feed.

## Features
- Real-time webcam capture
- HSV color space visualization
- Adjustable HSV ranges via trackbars
- Masked output preview

## Requirements
- Python 3.x
- OpenCV
- NumPy

## Installation

```bash
git clone https://github.com/alitalhq/hsv-color-tuner.git
cd hsv-color-tuner
python -m venv .venv
source .venv/bin/activate   # macOS / Linux
pip install -r requirements.txt
```

## Usage
```bash
python3 main.py
```
