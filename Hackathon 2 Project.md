# CancerDetect AI: Cancer Prediction and Type Classification

## Problem Statement
Identifying and classifying the various types of cancers accurately and at an early stage of development are essential to offering treatments. When evaluating medical images, radiologists often require some degree of assistance in identifying small areas that may represent an early-stage cancer.

## Our Mitigation
We presented "CancerDetect AI" - an AI-supported model that is capable of predicting cancer to a dependent degree and also able to present exactly what area of the medical scan has cancerous involvement.

## Features
- Cancer identification from medical images (X-ray / MRI / CT).
- Type classification (e.g. benign versus malignant tumours).
- Affected area highlighted with segmentation.

## Technology Stack (Planned / Prototype)
- **Machine Learning Framework**: TensorFlow / PyTorch
- **Computer Vision Techniques**: CNN (Convolutional Neural Network)
- **Data Pre-processing techniques**: OpenCV, Scikit-Image
- **Visualization techniques**: Matplotlib / Seaborn for plotting results
- **Deployment (Future plan)**: Web application (Flask/Django)

## Current Status
- A Basic CNN with 78% on the sample dataset
- We identified a way to highlight affected areas using GRAD-CAM (Gradient-weighted Class Activation Mapping)

## Future Direction
- Use larger medical datasets (ex. Chest X-ray Dataset, LIDC-IDRI).
- Model optimizations for real-time analysis of scans.
- Collaborate with healthcare facilities to develop clinical testing.

## Team Members
- Shantnu Biswas.
- Rajdeep Chatterjee.
- Utkarsh Khandelwal.

## Hackathon
- Hackathon Name: AI/ML Hackathon 1.O.
- Organized by: myOnsite Healthcare.
- Date: July 2024.
