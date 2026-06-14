# DecodeLabs-Internship-4

# 🍎 Fruit and Vegetable Classification using MobileNetV2 model

---

## 📌 Project Overview
This project is a deep learning image classification system that identifies 8 different fruits and vegetables using a pretrained MobileNetV2 model with Transfer Learning.

The model takes an image as input and predicts the class of the object in the image.

---

## 🧠 Problem Statement
The goal is to build an image recognition system that can classify images of fruits and vegetables into predefined categories using deep learning.

---

## 📂 Dataset
The dataset is organized into folders, where each folder represents a class:

- apple
- corn
- kiwi
- mango
- orange
- pineapple
- potato
- tomato

Each folder contains images of that specific class.

---

## 🔄 Training Strategy

- Technique: Transfer Learning
- Loss Function: Sparse Categorical Crossentropy
- Optimizer: Adam
- Epochs: 30
- Input Image Size: 224 x 224
- Batch Size: 32

---

## 📊 Results

- Training Accuracy increases gradually across epochs until reaches 100%

---

## 🖼️ Testing the Model

The model can predict the class of a new image:

Input: Image of a fruit or vegetable  
Output: Predicted class label (e.g., mango, apple, tomato)

The system also supports:
- Random image testing from dataset
- Visualization of predictions
