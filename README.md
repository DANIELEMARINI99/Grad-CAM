<a target="_blank" href="https://github.com/DANIELEMARINI99/Grad-CAM/blob/main/Grad_CAM.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

# Grad-CAM

Gradient-weighted Class Activation Mapping (Grad-CAM) is a class-discriminative localization technique that can generate visual explanations from any CNN-based network without any architectural requirement or re-training.
This approach uses the gradient flowing into the final convolutional layer to produce a localization map highlighting the important regions in the image for predicting the specific target.

# Task Description

The aim of the project it to apply Grad-CAM technique to a CNN trained on a brain tumor classification task and evaluate the visual explanation.

# Model and Dataset

The model used for the classification is ResNet50, which has been fine tuned by using the "Brain MRI images for brain tumor detection" [dataset](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection).

# Results
The results of the experiment were highly satisfactory, demonstrating a remarkable ability to accurately localize the tumor's exact region as we can see in figure below.

![image](https://github.com/DANIELEMARINI99/Grad-CAM/blob/main/Comparison.png)


