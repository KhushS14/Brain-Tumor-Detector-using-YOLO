# Brain Tumor Detection using YOLOv8
This project utilizes the YOLOv8 object detection model to identify and classify four types of brain tumors from medical imaging scans. The primary goal was to develop an accurate and efficient model capable of localizing and distinguishing between glioma, meningioma, pituitary tumors, and a notumor class.

The entire project was developed and trained within the Google Colab environment.

Key Features
1. Object Detection: Detects and classifies 4 categories of brain tumors.
2. High Performance: Achieves over 93% mAP50 on the unseen test set.
3. Efficient Model: The final model is the lightweight YOLOv8n version, which is fast and requires fewer computational resources.
4. Complete Workflow: Includes scripts and instructions for data preparation, training, validation, and testing.

Model Performance
An interesting finding of this project was that a smaller model (YOLOv8n) outperformed a larger one (YOLOv8s) on this specific dataset, highlighting that bigger isn't always better. The yolov8n model proved to be the most efficient and effective choice.


The final yolov8n model's performance on the test set is detailed below:

Precision: 92.6%
Recall: 87.2%
mAP50: 93.2%
<img width="2250" height="1500" alt="BoxPR_curve testing" src="https://github.com/user-attachments/assets/63ec2aa5-73e7-4959-b5fa-223144ff9fbf" />

Testing Ouput
<img width="1486" height="1990" alt="testing images" src="https://github.com/user-attachments/assets/ae02cc47-cfa1-40ca-9fed-632e44073541" />

