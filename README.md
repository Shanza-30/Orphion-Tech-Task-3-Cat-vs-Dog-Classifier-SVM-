# Cat vs Dog Classifier using SVM

This project demonstrates a simple **image classification pipeline** to distinguish cats and dogs using **Support Vector Machines (SVM)**. It covers data preprocessing, visualization, model training, evaluation, and prediction.

## 📌 Dataset
This project uses the **Dogs vs Cats dataset** from Kaggle:
👉 https://www.kaggle.com/c/dogs-vs-cats/data

Make sure to download the dataset from Kaggle and organize the images into appropriate `train/` and `test/` folders as shown below.

## 🗂 Project Structure
dataset

├── train/ # Training images (cats and dogs)

├── test/ # Test images
cat_dog_svm_model.pkl
# Trained SVM model
scaler.pkl 
# Trained scaler

## ⚙️ Features
- Load and preprocess images (resize, grayscale, flatten)
- Scale features using `StandardScaler`
- Train SVM classifier (`linear` kernel)
- Evaluate performance using accuracy and classification report
- Visualize class distribution and PCA-based feature separation
- Predict on new images with visual output
- Save and load trained model and scaler using `joblib`

  Place the images into the dataset/train/ and dataset/test/ folders.

Run the notebook or script to:

Preprocess images

Train SVM classifier

Evaluate model

Make predictions on test images

📊 Visual Outputs

Random sample images with labels

Class distribution bar chart

PCA visualization of features

Validation accuracy bar chart
