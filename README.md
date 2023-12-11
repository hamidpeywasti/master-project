# A Deep Convolutional Neural Network Based on the CIE LAB Color Space for Efficient Plant Disease Classification

This repository contains the implementation of my Master's thesis project at [Your University Name], focused on improving plant disease classification using a modified deep CNN architecture based on the CIE LAB color space.

## 🌿 Abstract

Plant diseases significantly reduce crop yield and quality, causing instability in food supply and substantial economic losses. In recent years, image processing, deep learning, and convolutional neural networks (CNNs) have been increasingly applied in agriculture, particularly for early detection and classification of plant diseases. Traditional CNNs typically use RGB images, but RGB channels are highly correlated and often sensitive to environmental conditions, making robust feature extraction more difficult.

In this study, we propose a deep convolutional neural network based on the CIE LAB color space. Our modified architecture is based on InceptionV3, where we process luminance (L channel) and chrominance (A and B channels) separately in two branches: one dedicated to grayscale data and another to color data. This separation allows the model to learn specialized filters for each type of input, leading to better feature extraction and a reduced number of trainable parameters, resulting in lower computational complexity compared to conventional approaches.

In addition, we observe that many existing models, despite performing well on public datasets, struggle to generalize in real-world conditions. To address this, we also evaluate our model using a custom dataset designed for real-world agricultural environments.