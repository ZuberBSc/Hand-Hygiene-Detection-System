# Hand-Hygiene-Detection-System
A deep learning–based computer vision system that recognises and classifies the eight key stages of proper handwashing according to WHO guidelines. The project uses TensorFlow and Xception architecture to train on thousands of images, ensuring accurate real-time classification for hygiene compliance and public health applications.

An AI-powered computer vision model designed to detect and classify proper handwashing procedures based on the World Health Organization’s (WHO) hygiene guidelines. This project demonstrates an end-to-end deep learning workflow, including dataset cleaning, image preprocessing, model training, and evaluation.

## Overview
The Hand Hygiene Detection System leverages Convolutional Neural Networks (CNNs), specifically a fine-tuned Xception architecture, to classify eight key stages of correct handwashing. Using a dataset of over 5,000+ curated images, the system was trained to support hygiene awareness during the COVID-19 era, showcasing the integration of AI in healthcare and behavioural safety.

## Dataset
* Source: Custom-labelled dataset from the CHS2406 Coursework Repository

* Classes: 8 distinct WHO handwashing stages

* Cleaning Process:

Removed corrupted, duplicate, and mislabelled images

Verified structural integrity using MD5 hash and pre-trained Xception predictions

* Sampling: 650 balanced images per class after cleaning

## Key Insights
* Successfully implemented a deep learning image classification pipeline from scratch

* Learned data validation and error correction techniques for noisy datasets

* Demonstrated practical AI application in healthcare and public safety

* Showcased model optimisation and transfer learning in real-world contexts
