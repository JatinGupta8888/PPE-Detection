# PPE-Detection (Personal Protective Equipment Detection)

# Introduction

This project is a computer vision application focused on detecting Personal Protective Equipment (PPE) compliance in video feeds. Using the YOLO (You Only Look Once) object detection model with OpenCV, this project identifies whether individuals in the frame are wearing required safety gear, such as hardhats, safety vests, and masks. The system is designed to enhance workplace safety by flagging non-compliant individuals in real-time, helping to prevent accidents and ensure adherence to safety regulations.


# Technical Overview:

YOLOv8 Model: Utilized for fast and accurate object detection. The model identifies objects frame-by-frame, determining their bounding boxes, class labels, and confidence scores.
OpenCV: Responsible for video handling, frame extraction, and image processing.
Python: The entire project is coded in Python, leveraging libraries such as cv2 (OpenCV) for video operations, and requests for downloading videos from URLs.

# Usage Instructions

1) Model Setup: Place the YOLO model file (best.pt) in the designated directory.
2) Video Input: Choose between using a live webcam, a local video file, or downloading a video from a URL.
3) Run the Detection: The program processes each frame, running the YOLO model to detect PPE compliance.
4) Display: The output video will show bounding boxes with color-coded compliance indicators and class labels for each detected object.




# Applications

1) Construction Sites: Monitor workers to ensure PPE compliance, reducing risks on-site.
2) Industrial Safety: Enforce compliance in factories or warehouses.
3) Public Safety: Detect PPE compliance in health-sensitive public areas.

