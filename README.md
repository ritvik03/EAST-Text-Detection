# EAST-Text-Detection
This repository detects texts presesnt in images using EAST algorithm implemented with OpenCV3.4+
Implementation:
Store the model file (frozen_east_text_detection.pb) in the same directory as the text_detection.py and text_detection_video.py 
# Running Predictions
$ python3 text_detection.py -i [IMAGE ADDRESS] -east [MODEL ADDRESS] -h [HEIGHT (must be multiple of 32)] -w [WIDTH (must be multiple of 32)]
Only OpenCV version >3.4.3 is supported (preferably 4)
Install OpenCV-contrib module before setting up the project
