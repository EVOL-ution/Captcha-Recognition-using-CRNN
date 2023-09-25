# Captcha Recognition using CRNN and CTC Loss
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1haykGyhrtkJkV5GlDMdrJstnvj0rYVmo?usp=sharing)

This repository contains code to build an optical character recognition (OCR) model for recognizing text in captcha images using a Convolutional Recurrent Neural Network (CRNN) architecture with Connectionist Temporal Classification (CTC) loss.

## Overview

The code demonstrates an end-to-end deep learning approach for recognizing text in captcha images, which involves:

- Downloading and preprocessing a dataset of captcha images and labels
- Defining and training a CRNN model with CTC loss for sequence recognition
- Visualizing the training history and analyzing model performance
- Decoding predictions on new samples using the trained model

The model architecture comprises convolutional layers for feature extraction, recurrent layers for sequence modeling, and CTC loss for training the OCR model without needing explicit character segmentation or alignment.

## Usage

The main Jupyter notebook is `Captcha_OCR.ipynb`. To use the code:

1. Install dependencies: tensorflow, matplotlib, etc.
2. Run the notebook cells sequentially to:
   - Preprocess the captcha dataset
   - Define, train and evaluate the CRNN-CTC model
   - Visualize predictions

The trained model can be used to make predictions on new captcha images. The notebook contains detailed explanations and visualizations to illustrate the working of the OCR model.

## Data

The notebook uses a sample dataset of captcha images from [this source](https://github.com/AakashKumarNain/CaptchaCracker). The images are in PNG format with labels as strings.

## Customization

The code can be adapted and customized:

- Use a different captcha dataset by modifying the data loading and preprocessing steps
- Adjust model hyperparameters and architecture as needed
- Add more visualizations and metrics for model analysis


## License

The source code is released under the MIT License - see [LICENSE](https://raw.githubusercontent.com/EVOL-ution/Captcha-Recognition-using-CRNN/main/LICENSE) for details.

