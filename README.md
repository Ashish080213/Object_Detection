# Object_Detection

This project is a real-time object detection application using OpenCV and a pre-trained deep learning model. It captures video frames from a webcam or camera, performs object detection on each frame, and displays the results with bounding boxes and labels.

The project utilizes the COCO dataset for class names and uses the SSD MobileNet v3 model for object detection. The model is loaded with its weights and configuration files, and the necessary settings for input size, scale, mean, and color channel swapping are applied.

The main loop continuously captures frames, detects objects using the loaded model, and overlays bounding boxes and labels on the frames for detected objects. The detected class names and confidence scores are printed for debugging purposes.

The project can be a starting point for various computer vision applications, such as object tracking, security systems, and video analytics. It demonstrates how to leverage pre-trained models and OpenCV's functionalities to perform real-time object detection.
