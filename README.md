# Project Name - Melanoma-CNN-Prediction
> In this assignment, you will build a multiclass classification model using a custom convolutional neural network in tensorflow.

Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant. The data set contains the following diseases:

- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)




## General Information
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging  Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

- Steps in project:
  1. Data Reading/Data Understanding
  2. Dataset Creation
  3. Dataset visualisation
  4. Model Building & training 
  5. Chose an appropriate data augmentation strategy to resolve underfitting/overfitting 
  6. Model Building & training on the augmented data
  7. Class distribution
  8. Handling class imbalances
  9. Model Building & training on the rectified class imbalance data


## Conclusions
- we got rid of overfitting using data augmentation. The class rebalance helped in reducing overfititng of the data and so the loss is beng reduced But it reduced the Acurracy very low
- Actinic Keratosos and Seborrheic keratosis class has least number of samples

- Pigmented benign keratosis dominates the data of count more than 100 in training

- Initially we used without the ImageDataGenerator which created data to over fit at high ratio

- Then we used dropout and ImageDataGenerator which reduced the overfitting

- At end we used Batch Normalization and Augumentation which helped in carry forward and reduce overfit


## Technologies Used
- numpy - version 1.20.3
- pandas - version 1.3.4
- matplotlib - version 3.4.3
- plotly - version 5.6.0
- seaborn - version 0.11.2
- statsmodels - version 0.12.2
- sklearn - version 0.24.2
- scipy - version 1.7.1 
- tensorflow - version 2.5.0


## Contact
Created by KajalKankariya - feel free to contact me!

