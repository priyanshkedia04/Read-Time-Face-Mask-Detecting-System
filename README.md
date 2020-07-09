# Read-Time-Face-Mask-Detecting-System

Read Time Face Mask Detecting System using OpenCV, Keras/TensorFlow, and Deep Learning. 

Easily detects whether you are wearing a Face Mask or not. Binary Classification was performed using a CNN Model giving highly accurate results .The Deep Learning model was built using the Pre-Trained Xception model (All Layers Freezed during training) who's output was given to  Fully Connected Dense layers trained using Dataset for Binary Classification between Masked and Un-masked Human Faces.


Real-time detection of Masked/Un-masked faces is done using OpenCV and Python. The detected area having a confidence value above 50% was given to the Fully Connected CNN for Classification. Need some more fine-tuning in Masked Face Detection as the artificially generated data was less.
