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

Model 	Epochs	Test mAP@.50	Training Time 	Conclusion
YOLOv8n	 30	       93.2%	      ~14 minutes	    Best Model: Highly accurate & efficient.
YOLOv8s	 100	    ~89.7% (val)	~55 minutes	    No performance gain.

The final yolov8n model's performance on the test set is detailed below:

Precision: 92.6%
Recall: 87.2%
mAP50: 93.2%
<img width="2250" height="1500" alt="BoxPR_curve testing" src="https://github.com/user-attachments/assets/63ec2aa5-73e7-4959-b5fa-223144ff9fbf" />
