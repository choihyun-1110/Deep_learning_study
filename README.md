# 🚗 Speed Estimation from Image Sequences

This project implements a deep learning model to estimate car speed using a sequence of 6 road scene images.

## 📌 Project Info

- 📅 **Date**: Nov 2024
- 🧠 **Course**: Basic AI @ Yonsei University
- 📁 **Data**: 400x121 RGB road images with speed labels
- 🎯 **Goal**: Predict the car’s speed at the last frame of a 6-image sequence

## 🛠️ Model Architecture

- 3D CNN for spatial-temporal feature extraction
- LSTM to capture time-dependent patterns
- Fully connected layers with dropout
- Loss: MAE (Mean Absolute Error)
- Optimizer: Adam (lr=1e-4)

## 🧪 Results

- ✅ **Best MAE**: 1.82
- Model successfully tracks speed decreasing trend in test set

## ▶️ Run in Colab

[📎 Open Notebook](https://colab.research.google.com/github/choihyun-1110/Deep_learning_study/blob/main/2020142046_%EC%B5%9C%ED%98%84.ipynb)






