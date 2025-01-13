# Melanoma_Detection_Assignment
Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

# General Information
Data Reading/Data Understanding → Defining the path for train and test images
Dataset Creation→ Create train & validation dataset from the train directory with a batch size of 32. Also, make sure you resize your images to 180*180.
Dataset visualisation → Create a code to visualize one instance of all the nine classes present in the dataset
Model Building & training : Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).
Choose an appropriate optimiser and loss function for model training
Train the model for ~20 epochs
Write your findings after the model fit, see if there is evidence of model overfit or underfit
Choose an appropriate data augmentation strategy to resolve underfitting/overfitting Model Building & training on the augmented data :
Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).
Choose an appropriate optimiser and loss function for model training
Train the model for ~20 epochs
Write findings after the model fit, see if the earlier issue is resolved or not. **Class distribution: **
Examine the current class distribution in the training dataset
Which class has the least number of samples.
Which classes dominate the data in terms of the proportionate number of samples. Handling class imbalances:
Rectify class imbalances present in the training dataset with Augmentor library. Model Building & training on the rectified class imbalance data:
Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).
Choose an appropriate optimiser and loss function for model training
Train the model for ~30 epochs

# Technologies used
Language : Python 3.8.8
Notebook : Jupyter notebook 6.3.0, Google colab
Library : Numpy, Pandas, matplotlib, sklearn, pathlib, tensorflow and keras
GPU : GPU runtime google colab

# Conclusions
At first, model was underfitting with basic sample images where training accuracy was approx 85% and validation accuracy was 84%

With basic tuning and help of ImageDataGenerator we were able to train the sample further and model seems to perform better where training and validation accuracy both were close to 55%.

With class imbalance and generating more sample images, we could notice model improved further and training and validation accuracy both > 82%.
