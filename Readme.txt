This repository includes two Kaggle notebooks designed for face detection and anonymization:

1. face-detection-and-anonymization-widerface-yolov8.ipynb

Dataset and Setup: This notebook loads the WIDER FACE dataset (automatic download code included). It uses YOLOv8 for detecting and anonymizing faces on randomly selected samples from both the validation and test sets on each running iteration.

Testing and Execution: Each iteration of the notebook runs with random images from the dataset, providing diverse testing scenarios. A code cell at the end enables you to upload and test your own images for face detection and anonymization.

2. face-detection-anonymization-test-video.ipynb

Video Anonymization: This notebook focuses on face detection and anonymization within video files. Tested on two random YouTube videos, the model demonstrated effective anonymization.

User Testing: You can specify your input video file path at the end of the notebook, which will anonymize the faces in the video. The processed video is then available for download.

Additional Notes:
1- Model File: The YOLOv8 model file is included. Please download and add it as an input in the Kaggle notebook. Ensure the correct model path is specified for testing.

2- Test Video Dataset: A link to the test video dataset is provided. Download and upload it to the test video notebook input folder to run the model on these videos.

3- Processed Video Added: The videos processed by the model after detecting and anonymizing faces are attached as the drive folder link.