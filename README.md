# Rock Paper Scissors Image Classifier

![](/src/assets/icon/xxxhdpi.png)

An ML model built with Keras Library to Classify Image that uploaded by Users to categorize it as Rock, Paper, or Scissors. Model was trained with dataset provided by Dicoding, which included 2000+ images of rock, paper, and scissors hands.

> This notebook was a submission for IBM Indonesia New Collar and Skill Acceleration Center X Dicoding 2020

<a href="https://colab.research.google.com/drive/16o_LtFxxgeBip6-vMLAqqH6qIty1zgdD?usp=sharing" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

## Technology Used
:heavy_check_mark: TensorFlow (Keras)

:heavy_check_mark: Matplotlib

:heavy_check_mark: SciKitLearn

:heavy_check_mark: Numpy


## Installation

1. Run all the notebook cell until you asked for image to upload. You can test the model with any picture.

2. After last cell is ran, the Model will be exported with name **"rps_model.h5"**

3. To use the model, use the following code:

```sh
from tensorflow.keras.models import load_model
model = load_model('rps_model.h5')
```
