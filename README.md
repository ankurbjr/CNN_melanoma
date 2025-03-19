# Melanoma Skin Cancer Detection
> Cancer encompasses over 200 different types, with melanoma being the deadliest form of skin cancer. The diagnostic process for melanoma typically begins with a clinical examination, followed by dermoscopic analysis and histopathological evaluation. Early detection is crucial, as it greatly improves the likelihood of successful treatment. The first step in diagnosing melanoma involves visually inspecting the affected skin area. Dermatologists use high-speed cameras to capture dermatoscopic images of skin lesions, achieving diagnostic accuracies between 65% and 80% without additional technological support. Further visual assessment by oncologists, combined with dermatoscopic image analysis, can enhance the overall predictive accuracy to 75%–84%. This project aims to develop an automated classification system utilizing image processing techniques to identify skin cancer based on images of skin lesions.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- ### Problem statement
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

- ### Dataset
> The dataset comprises 2357 images depicting malignant and benign oncological conditions, sourced from the International Skin Imaging Collaboration (ISIC). These images were categorized based on the classification provided by ISIC, with each subset containing an equal number of images.

- ### Architecture
  CNN Architecture used in the model building of this project consists of:
    - Data Normalization
    - Convolutional Layer
    - Pooling Layers
    - Dropout Layer
    - Flatten Layer*
    - Fully Connected Layers
    - Output Layer
    - Data Augmentation
    - Training
    - Model compliation 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
> Training medical images can be an uphill task if the image size is small and can cause overfitting problem but can be fixed by augmenting the available images. Also, the accuracy can further be improved with preprocessing operations like applying a filter to the image, tuning the parameters, using other network topologies.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- [Python](https://www.python.org/) - version 3.11.4
- [pathlib](https://wwww.pathlib.org/) - version 1.0.1
- [Matplotlib](https://matplotlib.org/) - version 3.10.0
- [Numpy](https://numpy.org/) - version 2.0.2
- [Pandas](https://pandas.pydata.org/) - version 2.2.2
- [Tensorflow](https://www.tensorflow.org/) - version 2.18.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- Upgrad learning
- [Introduction to CNN](https://www.analyticsvidhya.com/blog/2021/05/convolutional-neural-networks-cnn/)
- [Melanoma Skin Cancer](https://www.cancer.org/cancer/melanoma-skin-cancer/about/what-is-melanoma.html)


## Contact
Created by [@ankurbjr] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
