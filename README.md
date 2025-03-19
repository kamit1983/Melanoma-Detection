# Melanoma-Detection
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Project Background: Melanoma is the deadliest form of skin cancer, accounting for 75% of skin cancer deaths. Early detection is crucial for effective treatment, but manual diagnosis is time-consuming and prone to human error.
- Business Problem: The project aims to build an AI-based melanoma detection system that can classify nine types of skin diseases using deep learning, helping dermatologists improve diagnostic accuracy and efficiency.
- Dataset: The dataset consists of 2,357 images sourced from the International Skin Imaging Collaboration (ISIC), categorized into nine classes, including melanoma, basal cell carcinoma, and other benign/malignant skin conditions.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Model Performance & Overfitting: The initial model showed signs of overfitting, with training accuracy significantly higher than validation accuracy. Data augmentation and regularization techniques were applied to mitigate this issue.
- Impact of Class Imbalance: The dataset had an imbalanced class distribution, with some skin conditions having significantly fewer samples. Class rebalancing techniques, such as oversampling and augmentation, improved the model’s generalization.
- Effectiveness of Data Augmentation: pplying data augmentation (rotation, flipping, zooming, etc.) helped reduce overfitting and improved validation accuracy by making the model more robust to variations in image orientation and lighting.
- Final Model Performance: After implementing optimizations, the final CNN model achieved higher validation accuracy and better generalization. However, further improvements could be made using hyperparameter tuning and deeper architectures.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- TensorFlow - Version 2.x
- Keras - Version 2.x
- Augmentor - Version 0.2.x
- NumPy - Version 1.x
- Pandas - Version 1.x
- Matplotlib - Version 3.x
- Seaborn - Version 0.11.x

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by the need for early melanoma detection using deep learning techniques.
- The dataset used in this project was sourced from the International Skin Imaging Collaboration (ISIC).
- Special thanks to the creators of TensorFlow and Keras for providing robust tools for deep learning


## Contact
Created by @kamit1983 - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
