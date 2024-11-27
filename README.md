# Count Objects with YOLO

## Overview
This project employs YOLO (You Only Look Once) object detection to count objects in images or video streams. By integrating tools like Roboflow, it simplifies dataset management and annotation, ensuring precise and efficient object detection.
The implementation supports real-time processing and provides annotated outputs with object counts for various use cases, including surveillance, traffic monitoring, and inventory management.

## Features
Real-time Object Detection: Processes video streams and images to detect and count objects.
Integration with Roboflow: Uses Roboflow for dataset handling and annotations.
Customizability: Adjust detection thresholds and focus on specific object categories.
High Performance: Leverages GPU acceleration for faster processing.


Download the appropriate YOLO model weights (e.g., YOLOv5 or YOLOv8) from Ultralytics.
Place them in the designated weights/ directory.
Usage

## Notebook Execution
Open the count_objects_yolo.ipynb notebook and follow the steps to:
- Set up the environment.
- Load YOLO weights.
- Process input images or videos for object detection.
- Script Execution (Optional)

Thresholds: Adjust confidence and IoU thresholds in the code for better detection accuracy.
Classes: Specify object classes to include in the count (e.g., "car", "person").
Dataset Management: Use Roboflow to create, manage, and augment datasets.

## Results
Outputs are saved in the outputs/ directory, with bounding boxes and counts overlaid on images/videos.
Logs provide performance metrics, including detection times and object counts.

## Dependencies
- Python 3.8+
- YOLO libraries (ultralytics)
- OpenCV
- Roboflow API
- Supervision library
