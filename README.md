## Image classification and object detection for NEU dataset

This project was developed as part of a group assignment during our Master’s in Data Science program. It explores the use of deep learning models to solve image classification and object detection tasks, relevant to Business Intelligence applications.

# Project Overview

* Goal 1: Classify images into predefined categories using a ResNet50 model.
* Goal 2: Detect and localize objects in images using the YOLOv5 model.

This notebook demonstrates a full pipeline, from data preparation and preprocessing to training, evaluation, and visualization of results.

# Technologies Used

* Python 3.x
* PyTorch
* torchvision
* OpenCV
* Google Colab
* YOLOv5
* ResNet50 (pretrained)

# Models

🔹 Image Classification
* Model: ResNet50 (transfer learning)
* Framework: PyTorch
* Training: Custom dataset
* Output: Class label predictions and accuracy

🔹 Object Detection
* Model: YOLOv5
* Framework: Ultralytics YOLO
* Training: Pretrained weights, evaluated on test images
* Output: Detected objects with bounding boxes and confidence scores

# Datasets
We used small image datasets – one for classification and another for object detection. The goal was to keep it simple and focused on learning the workflow, rather than building a production-level system.

# Results

* The ResNet50 model performed well in classifying images after we fine-tuned it on our dataset.
* The YOLOv5 model detected multiple objects in real-world images, showing their class and confidence score.

We also included visual outputs in the notebook to show how the models performed, including predicted labels and bounding boxes on test images.
