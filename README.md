# Melanoma Detection using Custom Convolutional Neural Network

In this assignment, our objective is to develop a robust multiclass classification model using a custom convolutional neural network (CNN) in TensorFlow. The goal is to accurately detect melanoma, a potentially deadly form of skin cancer, leveraging image data.

## Problem Statement

Melanoma accounts for a significant portion of skin cancer deaths, highlighting the importance of early detection. By developing a CNN model capable of evaluating images and alerting dermatologists about the presence of melanoma, we aim to streamline the diagnostic process, potentially reducing manual effort and improving early detection rates.

## Dataset

- **Dataset Overview:** The dataset comprises 2357 images of malignant and benign oncological diseases sourced from the International Skin Imaging Collaboration (ISIC).
- **Disease Categories:** The dataset includes the following diseases:
  - Actinic keratosis
  - Basal cell carcinoma
  - Dermatofibroma
  - Melanoma
  - Nevus
  - Pigmented benign keratosis
  - Seborrheic keratosis
  - Squamous cell carcinoma
  - Vascular lesion


## Project Pipeline

1. **Data Reading/Data Understanding:** Define the paths for train and test images.
2. **Dataset Creation:** Create train and validation datasets from the train directory with a batch size of 32. Resize images to 180x180.
3. **Dataset Visualization:** Develop code to visualize one instance of all nine classes in the dataset.
4. **Model Building & Training:**
   - Create a CNN model to detect the nine classes.
   - Rescale images to normalize pixel values between 0 and 1.
   - Choose appropriate optimizer and loss function.
   - Train the model for approximately 20 epochs.
   - Analyze findings for evidence of overfitting or underfitting.
5. **Data Augmentation Strategy:** Implement data augmentation to resolve overfitting/underfitting.
6. **Model Building & Training on Augmented Data:**
   - Create a CNN model with data augmentation.
   - Rescale images and choose appropriate optimizer and loss function.
   - Train the model for around 20 epochs.
   - Evaluate if earlier issues are resolved.
7. **Class Distribution Analysis:**
   - Examine class distribution in the training dataset.
   - Identify classes with the least number of samples.
   - Determine classes

## Results before resolving the class imbalance :
![image](https://github.com/rupeshshuklavarroc/CancerCaseStudty/assets/120721317/8c8dbd8b-060b-4437-a72b-9d6a729d733b)

## Results after the resolving class imbalance :
![image](https://github.com/rupeshshuklavarroc/CancerCaseStudty/assets/120721317/e78e9c47-73bd-4ce7-bba4-15336ef3a84a)


   
