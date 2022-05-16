# ISIC Skin Cancer Classification using Custom CNN 
> CNN model which can accurately detect melanoma and classify skin conditions of 9 types 
> including Melanoma. Melanoma accounts for 75% of skin cancer deaths. A solution that can evaluate images and 
> alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- The model works to accurately classify the images into 9 conditions mentioned.
- Certain kind of Skin cancer Melanoma and other skin problems are being classified by the model.
- Classification of cancer via CNN model will certainly decrease manual effort for timely detection of condition and prioritize treatment.
- ISIC has provided sample images for total 9 kind of skin conditions including melanoma.
- The data set contains the following diseases:  Actinic keratosis, Basal cell carcinoma, Dermatofibroma, Melanoma, Nevus, Pigmented benign keratosis, Seborrheic keratosis, Squamous cell carcinoma, Vascular lesion


## Conclusions
- ISIC provided is not class balanced, data augmentation is used to create more image by augmenting existing.
- Image Size: 180 X 180 RGB  normalized between 0-1 used for training and validation.
- Resultant model is trained and validated upon augmented data for 30 Epochs
- Training Accuracy: 86.72  and Validation Accuracy: 82.70

## Technologies Used
- keras - version 2.8.0
- Pandas - version 1.2.4
- Numpy - version 1.20.1
- matplotlib - version 3.3.4
- seaborn - version 0.11.1
- Augmentor - version 0.2.10

## Acknowledgements
Thanks to ISIC for providing a well-structured dataset


## Contact
Created by [@santokhsdg] - feel free to contact me!
