# Covid Mask Classifier in TensorFlow

This repository contains a computer vision model that can be used for deciding whether someone has a correctly or incorrectly worn covid-19 mask or not.

There are 3 different classes:

  1. Incorrectly worn mask
  2. Correctly worn mask
  3. No mask
  
2 different datasets are used in this project.

First dataset [Flickr-Faces-HQ Dataset (FFHQ)](https://github.com/NVlabs/ffhq-dataset#flickr-faces-hq-dataset-ffhq) contains only faces and is created by [NVIDIA-Labs](https://github.com/NVlabs).

Second one contains incorrectly worn masks and correctly worn masks which are fully synthetic, meaning the authors have generated masks themselves and this dataset was created based on [Flickr-Faces-HQ Dataset (FFHQ)](https://github.com/NVlabs/ffhq-dataset#flickr-faces-hq-dataset-ffhq) dataset. 
You can see [their github page](https://github.com/cabani/MaskedFace-Net) for more details.


The model in this repo is trained on [Inception V3](https://keras.io/api/applications/inceptionv3/) and if you are planning to change the model structure, hyperparameters or backbone, you can instantly implement whatever you want. I parsed the code to facilitate recreation, you can find the sections in the notebook. 


The only thing you need in order to recreate your own model is that you have to fetch these datasets that i mentioned above.
