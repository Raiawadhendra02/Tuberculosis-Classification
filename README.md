
Tuberculosis Classification using DenseNet121 and Grad-CAM
This project focuses on the classification of Tuberculosis (TB) from chest X-ray images using a deep learning approach. The model leverages DenseNet121, a powerful convolutional neural network (CNN) architecture, to accurately classify whether a patient has TB or not. Additionally, Grad-CAM (Gradient-weighted Class Activation Mapping) is used to provide interpretability by highlighting the regions of the X-ray image that contributed most to the model's decision.

Key Features:
Dataset:

Utilizes a publicly available dataset of chest X-ray images, categorized into two classes: Normal and Tuberculosis.

Dataset is preprocessed (resized, normalized, and augmented) to improve model performance.

Model Architecture:

DenseNet121: A pre-trained CNN model is fine-tuned for binary classification (TB vs. Normal).

DenseNet's dense connectivity pattern ensures efficient feature reuse and improves accuracy.

Grad-CAM:

Grad-CAM is applied to visualize the regions in the X-ray image that the model focuses on for making predictions.

Helps in understanding the model's decision-making process and ensures transparency.

Evaluation Metrics:

Model performance is evaluated using metrics like Accuracy, Precision, Recall, F1-Score, and AUC-ROC.

Confusion matrix is used to analyze classification results.

Tech Stack:

Python

TensorFlow/Keras for deep learning model implementation.

OpenCV and Matplotlib for image processing and visualization.

Scikit-learn for evaluation metrics.

Applications:
Medical Diagnosis: Assists radiologists in detecting TB from chest X-rays.

Explainable AI: Provides interpretable results using Grad-CAM, making it suitable for healthcare applications.

Research: Can be extended to classify other diseases or improve model performance with larger datasets.

Future Enhancements:
Incorporate multi-class classification for different stages of TB.

Use larger and more diverse datasets to improve generalization.

Deploy the model as a web or mobile application for real-world use.

