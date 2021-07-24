# Image Segmentation
This was the second homework of the Artificial Neural Networks and Deep Learning course 2020/2021. All the details can be found on the [CodaLab Competition page](https://competitions.codalab.org/competitions/27176).

Developed by Diego Savoia and Francesco Emanuele Stradi.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/savoiadiego/Image-Segmentation/blob/main/Image%20Segmentation.ipynb)

The goal was to segment RGB images to distinguish between crop, weeds, and background.

### Implementation
The notebook is meant to be used in Google Colaboratory, loading the dataset from Drive as explained inside the notebook.
After the data preparation part, there are three different models to train and use for predictions:
* Fully Convolutional Neural Network model
* U-NET model
* Transfer Learning using VGG-16

Every model can be trained on the given dataset, using 20% of the samples for validation. Then, the prediction can be computed on the samples in the test folder. After that, the csv file containing the predictions is exported inside the Drive directory.
