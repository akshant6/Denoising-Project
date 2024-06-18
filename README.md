# Denoising-Project
This project presents the application and evaluation of the Zero-DCE model for enhancing low-light images. Zero-DCE, or Zero-Reference Deep Curve Estimation, is a novel technique that leverages deep learning to enhance image quality without requiring paired or unpaired training data. The model was trained on the provided dataset and was implemented using TensorFlow and Keras. The model's performance was evaluated using several custom loss functions and the Peak Signal-to-Noise Ratio (PSNR) metric. The results demonstrated a notable improvement in the visual quality of low-light pictures.

# Requirements
1. Numpy
2. Pandas
3. Tensorflow
4. Globe
5. PIL

# Architecture
<img width="329" alt="image" src="https://github.com/akshant6/Denoising-Project/assets/173190670/10d3c282-5d7c-499c-b22e-4196b38e9b4b">
A sequence of convolutional layers that estimate a set of curves to improve the input images are used to build the Zero-DCE model. Six convolutional layers with ReLU activations and two concatenation layers between them are used in the architecture to recover low level features. A final convolutional layer with a "tanh" activation is used to output the enhancement curves.


# Dataset
[Link](https://drive.google.com/drive/folders/1aTxiatoAtDvtoWC57fCySfxGqDWYiCQB?usp=drive_link)

# Paper
[Research Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Guo_Zero-Reference_Deep_Curve_Estimation_for_Low-Light_Image_Enhancement_CVPR_2020_paper.pdf)

# Results
PSNR Value: 27.966147730734242
