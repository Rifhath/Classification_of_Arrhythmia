# Arrhythmia Classification Using Deep Learning and 2D Spectral Image Representation

**Overview**

This repository contains the implementation of a deep learning pipeline for the classification of cardiac arrhythmias using 2D spectral image representations of ECG data. The project leverages convolutional neural networks (CNNs) to deliver an accurate and scalable solution for real-time arrhythmia detection, aimed at enhancing medical diagnostics.

**Key Features**

**ECG Data Preprocessing:** Transformed raw ECG signals into 2D spectral images and augmented the dataset using techniques such as flipping, rotation, and zooming to improve generalization.
**Deep Learning Architecture:** Designed and trained a multi-layer CNN with convolutional, pooling, fully connected, and dropout layers to classify six types of cardiac arrhythmias.
**Web Application:** Integrated a Flask-based web interface allowing users to upload ECG images and receive real-time predictions.
**Cloud Deployment:** Trained and tested the model on IBM Watson Studio for cloud scalability.

**Technologies Used**

**Frameworks:** TensorFlow, Keras
Programming Language:** Python
**Cloud Services:** IBM Watson Studio
**Visualization Tools:** Matplotlib

**Results**

Achieved ~96% accuracy using ten-fold cross-validation on the arrhythmia dataset.
Demonstrated robustness in detecting six types of arrhythmias, including Ventricular Fibrillation and Normal ECG.

**Future Enhancements**

Extend the dataset to include more arrhythmia types and multi-source ECG data.
Integrate advanced models like transformers for further performance improvements.
Deploy the application on a cloud platform (e.g., AWS, GCP) for wider accessibility.

Contact

**Author:** Rifhath Aslam Jageer Hussain
**Email:** rifhathaslam.jr.162@gmail.com
**LinkedIn:** [Rifhath Aslam](https://www.linkedin.com/in/rifhath-aslam-j-791a6a21b/)
