# Accident Detection Using Machine Learning
This project presents a real-time accident detection system leveraging the power of machine learning, specifically the YOLOv8 object detection model. The system is designed to analyze dashcam video footage, identify potential accidents.

## Features
+ Real-time Detection: Processes dashcam video data frame-by-frame to identify accidents as they occur.

+ YOLOv8 Integration: Utilizes the highly efficient YOLOv8 object detection model for accurate and fast inference.

+ Custom Dataset Training: Model trained on a custom-labeled dataset, ensuring high precision in accident and non-accident classification.

+ OpenCV for Video Processing: Employs OpenCV for robust video frame extraction and manipulation.

+ Video Output: Generates output videos with detected accidents highlighted (e.g., with bounding boxes and labels).

## Results
The trained YOLOv8 model demonstrates high accuracy in identifying accident events within various dashcam video footages. The system provides near real-time detection, making it suitable for practical deployment in scenarios requiring immediate accident alerts. The output includes processed videos with visual indicators (e.g., bounding boxes and labels) highlighting detected accidents.

See a quick demonstration of the detection:

![Accident Detection](outputs/output1.mp4)
