# Pothole Detection and Severity Classification

This project uses Deep Learning to analyse road images and classify the road condition into three categories:
1. Normal Road
2. Moderate Pothole
3. Severe Pothole

The system is built with TensorFlow and deployed using a Streamlit web interface that allows users to upload an image or paste an image URL for prediction.


## Project Motivation

Poor road conditions are one of the major reasons for road accidents and vehicle damage.  
Manual inspection of roads is time consuming and expensive.  

This project aims to create an automated system that can assist in identifying damaged roads quickly using Artificial Intelligence.


## Model Information

Transfer Learning Model: MobileNetV2  
Framework: TensorFlow / Keras  
Input Image Size: 224 × 224  

Final classes used for training:
- Normal
- Moderate
- Severe

The trained model is saved as:
severity_final.keras

## Project Files

app.py  
Streamlit frontend for user interaction

predict_module.py  
Loads trained model and performs predictions

train.ipynb  
Notebook used to train the deep learning model


## How to Run the Project

Install required libraries:

pip install streamlit tensorflow pillow numpy matplotlib requests

Run the application:

python -m streamlit run app.py

Open the browser:
http://localhost:8501



## Future Scope

• Real-time pothole detection using mobile or dash cameras  
• GPS tagging of detected potholes  
• Deployment on edge devices like Raspberry Pi  

