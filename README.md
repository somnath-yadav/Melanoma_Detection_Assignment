# Melanoma_Detection_Assignment
Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

At first, model was underfitting with basic sample images where training accuracy was approx 85% and validation accuracy was 84%

With basic tuning and help of ImageDataGenerator we were able to train the sample further and model seems to perform better where training and validation accuracy both were close to 55%.

With class imbalance and generating more sample images, we could notice model improved further and training and validation accuracy both > 82%.
