# Melanoma-Multiclass-Classification-CNN
> The main focus of the project is to build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early stag. It accounts for 75% of total skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Dataset being used](#dataset-being-used)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information

- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can help dermatologists detect the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis whereas also helping in detecting it in early stages.

- We have come up with a solution that can evaluate images and alert dermatologists about the presence of melanoma.
- We have built a multiclass classification model using a custom convolutional neural network in order to reduce a lot of manual effort that goes in diagnosis.


## Dataset being used

- We are using a dataset which consists of 2357 images of malignant and benign oncological diseases, which were formed from the ISIC (i.e. International Skin Imaging Collaboration). All images were grouped according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

- The data set contains the following diseases:
  - Actinic keratosis
  - Dermatofibroma
  - Basal cell carcinoma
  - Nevus
  - Melanoma
  - Seborrheic keratosis
  - Pigmented benign keratosis
  - Squamous cell carcinoma
  - Vascular lesion


## Technologies Used
- pandas - v1.5.3
- numpy - v1.23.5
- matplotlib - v3.7.1
- tensorflow - v2.13.0
- keras - v2.13.1


## Conclusions
- We were able to build a model that can detect melanoma with around ~75% accuracy.
- To get a good accuracy
  - We used image augmentation techniques to further enhance our dataset by creating multiple variants of existing images using zoom, horizontal flips and random rotation
  - We also handled class imbalance by increasing the number of images in each category by a count of 500.
  - We added a Dropout layer so that the model doesn't end up remembering the training dataset.


## Acknowledgements

- This project is inspired by group case study from upGrad and IIIT Bangalore Data Science program.
- References:-
- https://learn.upgrad.com/
- https://www.tensorflow.org/
- https://stackoverflow.com/
- Introduction to CNN from: https://www.analyticsvidhya.com/blog/2021/05/convolutional-neural-networks-cnn/
- Image classification using CNN from: https://www.analyticsvidhya.com/blog/2020/02/learn-image-classification-cnn-convolutional-neural-networks-3-datasets/
- Efficient way to build CNN architecture from: https://towardsdatascience.com/a-guide-to-an-efficient-way-to-build-neural-network-architectures-part-ii-hyper-parameter-42efca01e5d7



## Contact
Created by [@TanmayPriyadarshi @rinkal-rohara @lalithvamsi]
