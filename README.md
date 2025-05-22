
# MRI Brain Tumor Visualization

This repository contains brain MRI images and accompanying code for classification and visualization using Deep Learning techniques, specifically ResNet50 and Grad-CAM.

## 📁 Project Structure

```
/glioma_tumor/
/meningioma_tumor/
/no_tumor/
/pituitary_tumor/
README.md
LICENSE
.gitignore
```
Each folder contains sample MRI images of brain tumors from four categories.

## 🧠 Objective

The aim of this project is to detect and visualize brain tumors using convolutional neural networks (CNNs). The Grad-CAM technique is used to enhance explainability by highlighting image regions critical to the model's prediction.

## 🚀 Technologies Used

- Python 3.9+
- TensorFlow / Keras
- OpenCV
- Matplotlib
- NumPy
- Grad-CAM (via tf-keras-vis or custom implementation)

## 🧪 Main Steps

1. **Data Preprocessing**: Image resizing, normalization, augmentation.
2. **Model Training**: Using MobileNetV2 or ResNet50V2 with fine-tuning and class weights.
3. **Evaluation**: Confusion matrix, classification report.
4. **Visualization**: Grad-CAM heatmaps for interpretability.

## 🖼️ Sample Visualization

![Grad-CAM Example](./glioma_tumor/image(10).jpg)

## 📜 License

This project is licensed under the MIT License.

## 🔗 Related Work

This GitHub repo is part of the BSc dissertation on **Brain Tumor Detection from MRI Images using Deep Learning** (University of Derby, 2025).
