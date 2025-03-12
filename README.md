# AGV for Plant Disease Detection Using GoogleNet  

## Overview  
This project focuses on developing an Automated Guided Vehicle (AGV) equipped with a deep learning model to detect plant diseases in large-scale agricultural settings. The system integrates autonomous navigation using ROS 2 and Nav2, along with a Convolutional Neural Network (CNN) for plant disease classification.  

## Features  
- **Autonomous Navigation:** Utilizes ROS 2 and Nav2 for autonomous movement within a farm environment.  
- **Plant Disease Detection:** Implements transfer learning with the GoogleNet architecture trained on the PlantVillage dataset, achieving **98% validation accuracy**.  
- **LIDAR-based SLAM:** Enables real-time mapping and obstacle avoidance for seamless farm navigation.  
- **Onboard Computer Vision:** Deploys the trained model on the AGV to classify leaf diseases in real time.  
- **LLM Integration:** Provides farmers with accessible and detailed insights on detected diseases.  

## Technologies Used  
- **Deep Learning:** GoogleNet, Transfer Learning, CNNs  
- **Autonomous Navigation:** ROS 2, Nav2, LIDAR-based SLAM  
- **Hardware:** AGV Prototype, Onboard Camera, LIDAR Sensor  
- **Computer Vision:** OpenCV, PyTorch/TensorFlow  
- **LLM Integration:** NLP models for farmer assistance
