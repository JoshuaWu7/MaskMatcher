# MaskMatcher

MaskMatcher is an Internet-of-Thing device that uses a convolutional neural network to detect faces with or without a mask. The team used a Raspberry Pi which captures footage from a webcam, runs the machine learning model on it, then sends livestream data and mask prediction to a web app. The web app provides an user interface to control the operations (opening/closing a door) based on mask detection. 

## Tools:
- UBC ECE Linux VM: hosts the web application
- HTML/CSS/JS for the website frontend
- Flask for the backend
- OpenCV for image processing tasks
- PyTorch to develop the CNN mask detection model

Presentation Slide Deck: https://docs.google.com/presentation/d/1x-8Rft5wQSy5N0x97fIp2M2jpIU7IJCrHMujH891bnE/edit?usp=sharing
