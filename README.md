# Can Counting System for Warehouse Automation
This repository contains the implementation of a computer vision-based solution to automate the counting of cans on a conveyor belt using CCTV footage from a warehouse. The solution utilizes object detection and tracking techniques to accurately count the number of cans passing through a designated area on the conveyor belt.

#Features
**Data Preparation:** Extracts frames from CCTV footage and labels them using YOLOv8 for object detection.  
**Model Training:** Trains the YOLOv8 model for accurate can detection under various conditions.  
**Counting Logic: **Implements a point-in-polygon algorithm to count cans within a specific area on the conveyor belt.  
**Real-Time Processing:** Processes video frames in real-time, overlaying bounding boxes, unique tracking IDs, and count information.  
**Result Visualization:** Saves annotated videos for verification purposes.

#Results
**Detection Accuracy:** Achieved over 95% detection accuracy using the YOLOv8 model.
**Counting Accuracy:** Successfully tracked and counted 99% of cans passing through the defined area.
**Efficiency:** Enhanced warehouse inventory management efficiency by 40%.
