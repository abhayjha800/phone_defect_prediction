# Image Classifier with Streamlit and PyTorch




This repository contains the code for a web-based image classifier built using Streamlit and PyTorch. The classifier is trained on a dataset of images of different defects in mobile phone screens and can accurately predict the type of defect in a given image.

## Getting Started

To run the classifier, you will need to have Python 3.7 or later installed. You will also need to install the following libraries:

* PyTorch
* Streamlit
* Pillow
* Matplotlib

You can install these libraries using pip:
``` pip install torch torchvision streamlit pillow matplotlib ```



## Data source

The data to train the screen scratch model was obtained from : [kaggle](https://www.kaggle.com/datasets/girish17019/mobile-phone-defect-segmentation-dataset)

## Model Training

The classifier is trained on a dataset of 1200 images of different defects. The dataset is divided into a training set and a test set. The training set is used to train the model and the test set is used to evaluate the model's performance.   


The classifier is a convolutional neural network (CNN). The CNN is trained using the Adam optimizer and the cross-entropy loss function. The model is trained for 10 epochs.

## Model Evaluation

The classifier achieved an accuracy of 97% on the test set.
