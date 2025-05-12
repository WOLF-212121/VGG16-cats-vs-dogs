# VGG16-cats-vs-dogs
This repository consist of VGG16 pre-trained model for cats-vs-dogs Dataset

dataset link - https://www.kaggle.com/datasets/salader/dogs-vs-cats

tips before you start working on this dataset.

1. unzip the dataset and you will find folder named as 'dogs_vs_cats' which consist of 2 subfolder as 'test' and 'train'.

2. make a zip of the folder 'dogs_vs_cats' and upload the zip file in google drive.

3. from google.colab import drive

   drive.mount('/content/drive')
   
   run this code give access to google drive to colab.

4. Use T4 GPU for faster computation (don't try in VS-Code as computation process is slow)
