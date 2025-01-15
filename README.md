# Melanoma Skin Cancer Detection
> In cancer, there are over 200 different forms. Out of 200, melanoma is the deadliest form of skin cancer. The diagnostic procedure for melanoma starts with clinical screening, followed by dermoscopic analysis and histopathological examination. Melanoma skin cancer is highly curable if it gets identified at the early stages. The first step of Melanoma skin cancer diagnosis is to conduct a visual examination of the skin's affected area. Dermatologists take the dermatoscopic images of the skin lesions by the high-speed camera, which have an accuracy of 65-80% in the melanoma diagnosis without any additional technical support. With further visual examination by cancer treatment specialists and dermatoscopic images, the overall prediction rate of melanoma diagnosis raised to 75-84% accuracy. The project aims to build an automated classification system based on image processing techniques to classify skin cancer using skin lesions images.


## Problem Statement
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## What is the dataset that is being used?
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

## Conclusions
![image](https://github.com/user-attachments/assets/24aeec35-eed1-40cf-9b11-34ac6c925941)

1. Training and validation curves for accuracy and loss suggests that accuracy on both training and test data were increasing during all epochs and loss was decreasing.
2. Gap between the training and validation metrics has reduced significantly compared to previous model. Model is neither overfit nor underfit.
3. Validation accuracy is improved significantly after the class rebalancing. Earlier it was 31.36% and now it is 87.32%. After class rebalancing and retraining, the gap between training and validation accuracy has decreased considerably.
4. As per the final validation accuracy our model's performance on unseen data will be very good. Around 87%
