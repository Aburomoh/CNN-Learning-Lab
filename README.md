---
title: CNN Learning Lab
emoji: 🧠
colorFrom: blue
colorTo: purple
sdk: static
sdk_version: 1.33.0
app_file: index.html
pinned: false
---

# 🧠 CNN Learning Lab

![Demo GIF](https://huggingface.co/spaces/MohannadPhD/CNN-Learning-Lab/raw/main/demo.gif) *(Replace with actual demo GIF link)*

**An interactive educational tool that lets you teach a convolutional neural network (CNN) to recognize objects using your webcam!**

[![Open in Spaces](https://img.shields.io/badge/🤗-Open%20in%20Spaces-blue.svg)](https://huggingface.co/spaces/your-username/your-space-name)
[![TensorFlow.js](https://img.shields.io/badge/TensorFlow.js-FF6F00?logo=tensorflow&logoColor=white)](https://www.tensorflow.org/js)

## 🌟 Overview

CNN Learning Lab is an interactive educational application that allows you to:
- Capture images of two different objects using your webcam
- Train a convolutional neural network (CNN) entirely in your browser
- See real-time classification results
- Visualize what the CNN "sees" through feature maps and activations
- Understand how machine learning models learn from visual data

**All processing happens locally in your browser - no server required!**

## 🚀 How It Works

1. **Capture Samples**: Take photos of two different objects
2. **Train Model**: Build and train a CNN in your browser
3. **Classify**: See real-time predictions on new images
4. **Visualize**: Explore feature maps and activations

## 🖥️ User Interface

![Interface Diagram](https://huggingface.co/spaces/your-username/your-space-name/raw/main/interface.png) *(Replace with actual interface screenshot)*

### Main Components:
1. **Webcam Feed**: Real-time camera view
2. **Capture Controls**: Buttons to capture Object 1 and Object 2
3. **Training Controls**: Train Model and Reset buttons
4. **Status Panel**: Shows current status and sample counts
5. **Results Section**: Classification output and confidence
6. **Visualizations**: Feature maps and activation visualizations
7. **Instructions**: Step-by-step usage guide

## 🧪 Educational Value

This project demonstrates:
- How CNNs learn visual features from images
- The importance of training data variety
- How convolutional layers detect patterns
- The role of activation functions
- Model training and evaluation metrics

Perfect for students learning about:
- Computer vision fundamentals
- Neural network architectures
- Machine learning workflows
- Model interpretability

## 🛠️ Technical Implementation

### Tech Stack
- **Frontend**: Pure HTML/CSS/JavaScript
- **Machine Learning**: TensorFlow.js
- **Computer Vision**: Webcam API + Canvas API
- **Hosting**: Hugging Face Spaces (Static)

### Model Architecture
```mermaid
graph LR
    A[Input 100x100 Grayscale] --> B[Conv2D 16 filters]
    B --> C[MaxPooling2D]
    C --> D[Conv2D 32 filters]
    D --> E[MaxPooling2D]
    E --> F[Flatten]
    F --> G[Dense 64 units]
    G --> H[Output 2 units softmax]
