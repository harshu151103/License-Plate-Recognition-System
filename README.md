# License Plate Recognition System using YOLOv11 and EasyOCR

This project implements a License Plate Recognition system using the RoboFlow License Plate Recognition dataset and the YOLOv11 model for bounding box extraction. 
The system is designed to detect and extract license plates from vehicle images, followed by text extraction using EasyOCR.

# Project Overview
The system is developed with the following core objectives:

Bounding Box Detection:
* YOLOv11 is utilized to extract license plate bounding boxes from images.
* The model was trained for 10 epochs using the RoboFlow License Plate Recognition dataset.
* Achieved a Precision of 0.98 and Recall of 0.94.
  
OCR for License Plate Text Extraction:
* EasyOCR was employed to extract license plate text from detected bounding boxes.
* Image preprocessing techniques were applied to improve text extraction accuracy.

Visualization:
* Comparisons of original bounding boxes and extracted bounding boxes were plotted to ensure accuracy of detection.
* License plate text extraction results were also visualized for verification.


