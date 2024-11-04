# Age-and-Gender-Detection

This Python application uses OpenCV's deep learning module to perform real-time age and gender detection through your webcam.   It features a simple GUI built with Tkinter, allowing users to start the camera feed and view age and gender predictions overlaid on detected faces.

# Features

* Real-time age and gender detection with OpenCV's DNN module
* GUI with Tkinter for an intuitive interface
* On-screen labels for detected age range and gender

# Installation
To run this app, you'll need to install the following Python libraries. Open a command prompt and enter each command:

pip install opencv-python opencv-python-headless  
pip install pillow  


Note: Tkinter is included by default with most Python installations. If you encounter issues, install Tkinter with:  

Ubuntu/Linux: sudo apt-get install python3-tk  

# Model Files
Ensure the following pre-trained model files are available in the modelNweight directory:

opencv_face_detector.pbtxt  
opencv_face_detector_uint8.pb  
age_deploy.prototxt  
age_net.caffemodel  
gender_deploy.prototxt  
gender_net.caffemodel  

If you are looking for the model files, you can click the link below to download them:  

https://drive.google.com/drive/folders/1PWiSUg4tC_atEhNTIhlL2fJhQsCMVvzE?usp=sharing&pli=1  



# Requirements
Python 3.7+   
A webcam for real-time detection  

# Notes
This app provides a simple demonstration of age and gender detection using pre-trained models with OpenCV's DNN.   It can be customized further for applications that require demographic analysis or user profiling.  


