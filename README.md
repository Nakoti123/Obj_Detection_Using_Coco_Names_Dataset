# Obj_Detection_Using_Coco_Names_Dataset and SSD_MobileNet Model
This repository contains code for performing object detection using the COCO dataset's object names and the Single Shot MobileNet model. The goal is to detect and localize objects in images using a pre-trained deep learning model.

# Features
-> Object detection using the COCO dataset's 80 object categories.

-> Utilizes the lightweight Single Shot MobileNet architecture for efficient inference.

-> Provides bounding box coordinates and class labels for detected objects.

-> Easy-to-use script for running object detection on images or videos.

# Usage
-> Download the pre-trained weights for the Single Shot MobileNet model from the TensorFlow Model Zoo.

-> Install the required dependencies using pip install -r requirements.txt.

-> Run the object_detection.py script, providing the path to the input image or video file.

-> The script will perform object detection and display the results, including bounding boxes and class labels, on the output.

# COCO Names
The COCO dataset provides a comprehensive list of object categories. The coco_names.py file contains the mapping of class IDs to their corresponding names.

# Model Performance
The Single Shot MobileNet model offers a balance between speed and accuracy, making it suitable for real-time object detection tasks.

# Future Improvements
-> Explore other pre-trained models for object detection and compare their performance.

-> Implement post-processing techniques like non-maximum suppression for better object localization.

-> Provide options for adjusting the detection threshold and other parameters to fine-tune the model.
