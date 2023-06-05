# Melanoma_Detection_CNN
> We build a CNN based model which can accurately detect melanoma.
 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Results](#results)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths.
- A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- In this project, we use CNN based models that take images of malignant and benign oncological diseases and classify them into 9 classes of different diseases and cancers.
- The training and validation data is formed from the International Skin Imaging Collaboration (ISIC).
- We build upon one CNN based model architecture, and train it with different augmentation techniques.
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Results
- The vanilla trained model (model 1) has achieved a training accuracy of ~95% and validation accuracy of ~45%, indicating high overfitting.
- Simply by augmenting double the data for each class, the new model (model 2) has achieved a training accuracy of ~88% and validation accuracy of ~55%.
- A third model (model 3) was built using the same architechture but this time we rebalanced the classes using a different augmentor, which has achieved a training accuracy of ~95% and validation accuracy of ~70%.

## Conclusions
- Less data has been a reason for overfitting, which got reduced in model 2 (Doubling the data increased validation accuracy by 10%)
- Data imbalance has been a reason for overfitting (Class rebalancing has further increased validation accuracy by 15%)

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Augmentor - version 0.2.12
- Keras - version 2.12.0
- Tensorflow - version 2.12.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->



## Contact
Created by [@showman-sharma] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
