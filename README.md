🚀 Identification of Frost in Martian HiRISE Images

This project focuses on classifying Martian terrain using high-resolution HiRISE images to detect frost presence. By leveraging advanced deep learning techniques—particularly CNNs and MLPs — this work enhances planetary surface analysis.

🧠 Model Overview

Architecture: A hybrid deep learning pipeline combining:

Convolutional Neural Network (CNN) for spatial feature extraction.  
Multi-Layer Perceptron (MLP) for classification based on learned features.  
Transfer Learning: Employed pre-trained models to boost performance:  

✅ EfficientNetB0  
✅ ResNet50  
✅ VGG16  

Custom Model: Benchmarked against a handcrafted CNN+MLP architecture to evaluate robustness.  

🛰️ Dataset  
Source: NASA HiRISE public datasets  

Classes: Frost vs. Non-Frost Martian terrain

Preprocessing:  
Image resizing and normalization  
Augmentation: rotation, flipping, zoom  
Dataset split: Training, Validation, Test  

