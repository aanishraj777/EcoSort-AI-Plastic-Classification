# ♻️ EcoSort AI: Intelligent Waste Classification using Deep Learning (CNN)

[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![TensorFlow 2.14+](https://img.shields.io/badge/TensorFlow-2.14+-orange.svg)](https://www.tensorflow.org/)
[![Gradio 4.0+](https://img.shields.io/badge/Gradio-4.0+-green.svg)](https://gradio.app/)

## 🚀 Project Overview
This repository implements an automated **Waste Classification System** using a **Convolutional Neural Network (CNN)**. The project addresses the critical challenge of waste segregation by accurately identifying and categorizing waste items into organic and inorganic classes.

The goal is to improve recycling efficiency and reduce landfill contamination through real-time AI-powered image analysis.


## 🛠️ Key Features
* **CNN-Based Feature Extraction:** Optimized convolutional layers for high-accuracy visual pattern recognition.
* **Real-time Classification:** Instant categorization of waste items into Organic and Inorganic (Recyclable) streams.
* **Performance Visualization:** Comprehensive training/validation loss and accuracy plots included for model evaluation.
* **Interactive UI:** Gradio-powered web interface for seamless model demonstration and testing.

## 🧠 System Architecture (CNN Workflow)
The model follows a hierarchical feature extraction process:
1. **Input Layer:** Processes 224x224 RGB images.
2. **Convolutional Blocks:** Multiple layers using ReLU activation for capturing edges, textures, and object shapes.
3. **Max Pooling:** Downsampling layers to reduce spatial dimensions and retain critical features.
4. **Dense Head:** Fully connected layers with Dropout for classification and generalization.
5. **Output Layer:** Sigmoid activation for binary classification (Organic vs. Recyclable).


## 📊 Performance & Evaluation
The model's performance is monitored during training to ensure high precision and recall.
* **Accuracy:** Evaluated on a diverse test set of household waste images.
* **Loss Curves:** Analysis of categorical cross-entropy to optimize model convergence.

## ⚙️ Installation
Clone the repository:
```bash
git clone [https://github.com/](https://github.com/)[your-username]/EcoSort-AI-Plastic-Classification.git
cd EcoSort-AI-Plastic-Classification
