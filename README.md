
# Project Title: Potato Leaf Disease Classification

## Aim:
The primary aim of this project is to develop a machine learning model that can accurately classify various diseases in potato leaves based on images. This will assist farmers in early diagnosis and effective treatment, leading to better crop management and yield.

## Abstract:
This project employs convolutional neural networks (CNNs) to classify potato leaf diseases. The CNN model processes images of potato leaves, identifying specific disease patterns and classifying them into categories such as early blight, late blight, and healthy leaves. The model demonstrates high accuracy and can significantly aid in preventing crop losses due to diseases.

## About Dataset:
The dataset used comprises images of potato leaves with various disease symptoms. These images have been collected from multiple sources and annotated by plant pathology experts.

<p align="left">
<strong>1. Early Diseased Leaf Images:</strong><br>
<img src="https://github.com/agadhiya/Potato_disease_Classification/blob/main/potato_late_blight.jpg" width="50%">
</p>

<p align="left">
<strong>2. Late Diseased Leaf Images:</strong><br>
<img src="https://github.com/agadhiya/Potato_disease_Classification/blob/main/potato_early_blight.jpg" width="50%">
</p>

<p align="left">
<strong>3. Healthy Leaf Images:</strong><br>
<img src="https://github.com/agadhiya/Potato_disease_Classification/blob/main/potato_healthy.jpg" width="50%">
</p>


## Image Preprocessing:
Key preprocessing steps include:
1. **Resizing:** Adjust the image dimensions to fit the input size of the CNN.
2. **Normalization:** Scale pixel values for better model performance.

## Image Augmentation:
Image augmentation techniques such as rotation, scaling, and flipping are applied to increase the diversity of the training dataset and improve the robustness of the model.

## Convolutional Neural Network Evaluation:
![model](https://github.com/agadhiya/Potato_disease_Classification/blob/main/result.png)

## Results:
The classification results show an accuracy of over 90%, demonstrating the effectiveness of the CNN in disease detection.

## Conclusion:
The project highlights the potential of deep learning in agriculture, particularly in disease management. Future work will focus on expanding the dataset and integrating the model into a real-time disease detection system.
