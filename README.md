Intel Image Classification (TL vs. FT)
This project investigates the performance differences between Transfer Learning and Fine-Tuning using a pre-trained ResNet-18 architecture. The goal is to accurately classify images from the Intel Image Classification dataset (buildings, forests, glaciers, mountains, sea, and streets) into six distinct categories.

Project Overview
By leveraging models pre-trained on ImageNet, this project demonstrates how to optimize deep learning workflows to achieve high accuracy with reduced computational costs. It highlights the practical trade-offs between freezing layers (Transfer Learning) and updating model parameters (Fine-Tuning).

Key Features
Methodology Comparison: A side-by-side technical evaluation of model adaptation strategies.

Deep Learning Pipeline: Full workflow using PyTorch and torchvision for data loading, augmentation, and training.

Interactive Deployment: Includes a Gradio web interface that allows users to upload images and receive real-time predictions.

Performance Metrics: Visualization of training progress, including loss and accuracy curves to monitor convergence.

Tech Stack
Frameworks: PyTorch, torchvision, Gradio

Data/Utils: pandas, numpy, PIL, matplotlib

Platform: Optimized for GPU acceleration (Google Colab T4)
