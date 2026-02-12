# Automatic Bandage Overlay using Computer Vision

## Overview
This project detects wound-like regions on skin images and automatically
places a realistic bandage using OpenCV.

## Methodology
- HSV-based wound color segmentation
- Edge detection using Canny
- Contour filtering based on area and aspect ratio
- Bandage scaling, rotation, and brightness matching
- Alpha blending for realistic overlay

## Technologies
- Python
- OpenCV
- NumPy
- Matplotlib

## Use Case
Healthcare simulation, first-aid training, AR medical assistance.
