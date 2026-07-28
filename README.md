Project Title: AI-Based Detection of Diabetic Retinopathy in Retinal Images

Problem Statement :
Traditional diagnosis relies on manual examination of retinal images by specialists, which can be time-consuming and resource-intensive. This project aims to address the need for an automated, accurate, and efficient screening method using deep learning techniques

<img width="3699" height="971" alt="image" src="https://github.com/user-attachments/assets/b16db206-bff3-4cfa-bb1b-e0d351933afa" />




Project Objectives: 
 1. Design and implement a deep learning model for diabetic retinopathy detection.
 2. Evaluate model performance using standard classification metrics.

Methodology
1. Dataset Collection
  Collected retinal fundus images from publicly available datasets.
  Combined and organized the images into binary classes: Healthy and Diabetic Retinopathy.
2. Data Preprocessing
   Resized all images to a fixed input size.
   Applied image normalization and augmentation techniques to improve model generalization.
   Split the dataset into training, validation, and testing sets.
3. Model Development
   Implemented a custom Convolutional Neural Network (CNN) using PyTorch.
   Evaluated transfer learning with ResNet50.
   Experimented with different loss functions, including Binary Cross-Entropy (BCE) and Focal Loss.
4. Model Training
   Trained each model using the training dataset.
   Tuned hyperparameters such as learning rate, batch size, and number of epochs.
   Monitored validation performance to reduce overfitting.
5. Performance Evaluation
   Compared all models using metrics such as:
   Accuracy
   Precision
   Recall (Sensitivity)
   F1-score
   ROC-AUC
   Generalization Testing
   Evaluated the best-performing model on external datasets (Messidor and APTOS) to assess its robustness and ability to generalize to unseen data.


