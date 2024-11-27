# Melanoma-Detection-Assignment
- To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

>The data set contains the following diseases:

- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion

## Conclusions - Findings from the CNN Training Results:
- Training Accuracy: Starts low at 27.20% (epoch 1) and improves steadily to 73.04% (epoch 29), indicating progressive learning.
- Rises from 14.03% (epoch 1) to 74.61% (epoch 29), suggesting improved generalization
- High initial loss (34.89) decreases steadily to 3.76 (epoch 29), reflecting learning progress but indicating struggles with convergence.
- Rectifying the class imbalance using Augmentor helped in improving both training and validation results.
- The model shows promise with significant improvements in accuracy over time, achieving a respectable validation accuracy of 74.61% by epoch 29

## Technologies Used
- tensorflow
- Pandas
- numpy
- matplotlib
- glob
- PIL
- os
- pathlib

## Contact
Created by [@githubRuchi-Dib] - feel free to contact me!
