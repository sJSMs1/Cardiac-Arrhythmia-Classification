# Cardiac-Arrhythmia-Classification
"Automated Classification of Cardiac Arrhythmia using Deep CNN (VGG16) on ECG Images with 98.34% accuracy."


Automated Classification of Cardiac Arrhythmia using Deep CNN
📌 Project Overview
This project focuses on the automated detection and classification of cardiac arrhythmias using Deep Learning. By transforming ECG signals into 2D images, we leverage the power of Convolutional Neural Networks (CNN) to provide a reliable alternative to manual ECG interpretation.
+4

🚀 Key Results

Accuracy: Achieved a final test accuracy of 98.34% using the VGG16 architecture.
+1


Dataset: Processed a large-scale dataset of 124,000+ ECG images derived from MIT-BIH and PTB databases.
+2


Classification: Successfully classified heartbeats into 6 categories: Normal (N), Supraventricular (S), Ventricular (V), Fusion (F), Unclassifiable (Q), and Myocardial Infarction (M).
+1

🛠️ Tech Stack & Methodology

Language: Python.


Frameworks: TensorFlow & Keras.
+1


Architecture: Transfer Learning using VGG16 (pre-trained on ImageNet).
+2


Preprocessing: Image resizing (224x224), Normalization, and Data Augmentation (Rotation, Zoom, Shifts).
+1


Optimization: Trained using Adam Optimizer (learning rate = 0.0001) with Categorical Cross-entropy loss.
+1

📊 Performance Analysis
The model shows exceptional precision and recall for major classes like Normal (N) and Myocardial Infarction (M). Future improvements will focus on handling class imbalance for minority classes (Fusion and Supraventricular) using oversampling or class weighting.
