# Brain Tumor MRI Predictor
2 predictive CNN models created from scratch for predicting brain tumor MRI images

This repository includes 4 files. Each CNN has 2 files, one used for studying the training process and the second one for studying the testing and prediction process.

### About the dataset
The first dataset used is obtained from KAGGLE [Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset), with approximately 7000 images of 3 types of brain MRI tumor images and non tumor images. A second dataset is used in the first file for training also obtained from KAGGLE: [Br35H: Brain Tumor Detection 2020](https://www.kaggle.com/datasets/ahmedhamada0/brain-tumor-detection) containing approximately 1500 images of brain tumor or non tumor MRI images.

### About the data
The type of images in this data are made in all 3 planes: axial, coronal and saggital. The dataset contains also T1, T2 and FLAIR images from MRI.

### Method
The first dataset has 4 outputs while the second dataset has only 2 outputs (tumor and no-tumor). 2 CNNs were created from scratch one predicting if the image has tumor or not and the second CNN predicts the type of tumor, including meningioma, glioma, and pituitary. Simple models were created in order to follow the performance and open the path to future works.

### How to use the code for training
Download the datasets and the training codes. Store them and in the training and testing paths variables of the code write the location of the dataset. For the 2 classes classifier, combine the first dataset where all the tumor types will be part of a single folder called 'yes'. For this model, 2 datasets were used, the second due to reduce overfitting.

### How to use the code for predicting
Store the models (.h5 files) and load them in your console. Use the testing folders for predicting and see the results. Moreover, you can upload images at your own and predict them changing the name in the image_path variable.
