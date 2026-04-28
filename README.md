# Real-Time Object Tracking

A simple computer vision project that performs real-time object tracking using a webcam and OpenCV. The system detects and tracks objects based on color and draws bounding boxes around them in live video.

## Overview

This project was built to strengthen my understanding of core computer vision concepts such as image segmentation, contour detection, and real-time video processing. It was inspired by my interest in applying vision systems to robotics and perception tasks.

## Features

- Real-time video capture using webcam  
- Color-based object detection (HSV filtering)  
- Contour detection to identify objects  
- Bounding box visualization around detected objects  

## Technologies Used

- Python  
- OpenCV (`cv2`)  
- NumPy  

## How It Works

1. The webcam captures live video frames  
2. Frames are converted from BGR to HSV color space  
3. A mask is applied to isolate a specific color range  
4. Contours are detected from the mask  
5. Bounding boxes are drawn around detected objects  

## Getting Started

### Prerequisites

Make sure you have Python installed, then install dependencies:

```bash
pip install opencv-python numpy
