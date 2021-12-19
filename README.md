# Malaria-Classification-CNN-Vs-ResNet50-Vs-VGG19-Vs-InceptionV3

## PROBLEM STATEMENT
The aim of the task is to save human life by detecting and deploying the image cells that contain malaria or not. 
Dataset contains images divided into categories:

1) Infected
2) Uninfected


## Approach

* Classifying different images of cells into the categories : Infected and Uninfected.
* Trained the model on 27,558 images.
* Took a test split of 20%.
* Performed data augmentation using techniques like: rotation, translation, zooming, cropping, and flipping.
* Models trained with CNN, ResNet50, VGG19 and InceptionV3.

## Languages Used 
**Python Version:** 3.9.0

## Resources and Tools Used
**Tools:** Jupyter Notebook

**Packages:** Pandas, NumPy, sklearn, TensorFlow, Keras, cV2.  

## Data Used
* **Data taken from kaggle** : https://ceb.nlm.nih.gov/repositories/malaria-datasets/

## Data Wrangling and Data Visualization
* Preparing the image path and storing them in a dataframe along with their labels.
* Visualizing the distribution of classes and the pictures of cells.
* Augmenting the data using an image data generator.
![alt text](https://github.com/fahadmehfooz/Malaria-Classification-CNN-Vs-ResNet50-Vs-VGG19-Vs-InceptionV3/blob/main/images/__results___21_1.png)

## Model Building 

First, I took a split on the data with training data as 80%. I tried to compare a classic CNN with the above mentioned pretrained models.

Models Used:

* CNN
* InceptionV3
* VGG19
* ResNet50

Best reults were obtained for VGG19.

## Model performance

**Results:**

* CNN - Train accuracy: 50%,  Validation accuracy: 59%
* InceptionV3 - Train accuracy:52% ,  Validation accuracy: 49%
* VGG19 - Train accuracy: 92%,  Validation accuracy: 95%
* ResNet50 - Train accuracy: 89%,  Validation accuracy: 93%
