## AI-Powered Brain Tumor Diagnosis with Explainable AI 

Welcome to the "Glass Box" Brain Tumor Classifier, a project that goes beyond prediction to provide understanding. This repository contains an end-to-end deep learning pipeline that not only classifies brain tumors from MRI scans with high accuracy but also explains *why* it makes its decisions using cutting-edge Explainable AI.

## The Vision: From Black Box to Glass Box

In high-stakes fields like medicine, a correct prediction isn't enough; we need to build trust. This project tackles that challenge head-on.

- **The Problem:** A standard AI model is a "black box." It gives an answer but no reasoning. For a doctor, this is untrustworthy and unusable for critical decisions.
- **Our Solution:** We've built a "glass box." Our model uses **Grad-CAM** to produce a visual heatmap, highlighting the exact regions in the MRI scan that led to its diagnosis. This transforms the tool from a simple classifier into a trustworthy diagnostic assistant that empowers medical professionals.

The final deliverable is an interactive web application where a user can upload an MRI and instantly receive not just a prediction, but visual proof of the model's reasoning.

## Core Technologies & Concepts Demonstrated

- **Programming Language:** Python
- **Deep Learning Framework:** TensorFlow 2.x with the Keras API
- **Modeling Technique:** Transfer Learning using pre-trained architectures (e.g., ResNet50, InceptionV3) for feature extraction.
- **Explainable AI (XAI):** Implementation of Grad-CAM (Gradient-weighted Class Activation Mapping) to visualize model attention.
- **Interactive Deployment:** A simple and elegant web application built with Gradio for real-time model interaction.
- **Data Science Workflow:** Comprehensive Data Augmentation, Preprocessing, and robust Model Evaluation (using Confusion Matrix, Precision, Recall, and F1-Score).

## Project Structure

This repository follows a professional, modular structure to ensure the code is clean, scalable, and easy to maintain.