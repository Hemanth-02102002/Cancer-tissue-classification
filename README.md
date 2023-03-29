# Cancer-tissue-classification

Early diagnosis of cancer focuses on detecting symptomatic patients as early as possible so
they have the best chance for successful treatment. When cancer care is delayed or inaccessible there is a lower chance of survival, greater problems associated with treatment and higher costs of care. Early diagnosis improves cancer outcomes by providing care at the earliest possible stage and is therefore an important public health strategy in all settings.

This model can predicte if a tissue is cancerous or not.

The data set was taken from Histopathologic Cancer Detection dataset.
https://www.kaggle.com/competitions/histopathologic-cancer-detection/data

From the Tensorflow library the keras package is imported and the necessary training process is processed.
The input is fed as an image format where it is pre-processed by calling the ImageDataGenerator from keras.
The Neural Network is designed as given by the below picture and a model is exported.
In the prediction file, an input can be fed and it can predict whether the given tissue is a Cancerous or Non-Cancerous.

![Screenshot 2023-03-29 203652](https://user-images.githubusercontent.com/85058862/228584647-65268e87-ea90-46b2-9c9e-41740d38ea3b.png)



![Screenshot 2023-03-29 203728](https://user-images.githubusercontent.com/85058862/228584868-05e7d619-e7d1-4556-bcbf-b91c2bd06bfd.png)
