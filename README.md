x# 🌱 Plant Disease Detection Using Deep Learning

## 📌 Project Overview
Plant Disease Detection is a Deep Learning project that
uses a Convolutional Neural Network (CNN) to classify
plant leaf images into different disease categories.

The main objective is to explore how AI and Deep Learning
can help identify potential plant diseases from leaf images.

## 🎯 Objectives
- Classify plant leaf images into disease categories.
- Learn image classification using CNN.
- Apply image preprocessing techniques.
- Evaluate model performance using validation data.
- Explore AI applications in agriculture.

## 🛠️ Technologies Used
- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Google Colab
- GitHub

## 📂 Dataset
This project uses the PlantVillage dataset, obtained
through the KaggleHub dataset downloader.

The dataset contains images of healthy and diseased
plant leaves across multiple categories.

Dataset source:
https://www.kaggle.com/datasets/emmarex/plantdisease

## ⚙️ Project Workflow

1. Import required Python libraries.
2. Download and inspect the dataset.
3. Identify plant disease categories.
4. Split images into training and validation sets.
5. Resize images to 128 × 128 pixels.
6. Normalize pixel values from 0–255 to 0–1.
7. Build a CNN classification model.
8. Train the model using training images.
9. Evaluate performance on validation images.
10. Predict the category of a leaf image.
11. Save the trained model.

## 🧠 Model Architecture
The CNN model includes:

- Convolutional layers for feature extraction.
- Max Pooling layers for spatial downsampling.
- Flatten layer to convert features into a vector.
- Dense layer for classification learning.
- Dropout layer to help reduce overfitting.
- Softmax output layer for class probabilities.

## 📊 Model Evaluation
The model is evaluated using validation loss and
validation accuracy.

Actual accuracy depends on training results,
dataset quality, and model generalization.

## 🚀 How to Run the Project

1. Open Google Colab.
2. Upload or open `Plant_Disease.ipynb`.
3. Run the notebook cells in order.
4. Download the dataset when prompted by the code.
5. Train the CNN model.
6. Evaluate the model and test predictions.

## 💾 Model Saving
The trained model can be saved in Keras format:

`plant_disease_model.keras`

## 🔮 Future Improvements
- Improve model accuracy through hyperparameter tuning.
- Apply data augmentation.
- Test predictions on new leaf images.
- Develop a simple web application for image uploads.
- Explore deployment for practical use.

## ⚠️ Disclaimer
This is an educational project. Predictions may be
incorrect and should not be treated as a definitive
plant health diagnosis.

## 👩‍💻 Author
Simran Gupta

GitHub: https://github.com/SIMRAN2111
