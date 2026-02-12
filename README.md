# Bandage Overlay CV

## Overview
This project implements an automated computer vision system that detects wound-like regions on skin images and overlays a realistically transformed bandage. The system identifies the wound area, estimates its orientation and size, and applies a bandage with appropriate scaling, rotation, and brightness adjustment to achieve a natural visual appearance.

## Approach
- Color-based wound detection using HSV segmentation
- Edge detection and contour analysis to localize the wound
- Selection of the most probable wound region based on geometric constraints
- Dynamic bandage transformation (scaling, rotation, brightness matching)
- Alpha blending for realistic overlay

## Technologies Used
- Python  
- OpenCV  
- NumPy  
- Matplotlib  

## Use Cases
- Healthcare and first-aid training simulations  
- Medical image processing demonstrations  
- Augmented reality assistance for basic wound care  
