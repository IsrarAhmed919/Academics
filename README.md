# Image Classification using Feature Extraction and Machine Learning

## Contents
1. [Introduction](#introduction)
2. [DataSet](#DataSet)
3. [Feature Extractor and Machine Learning Algorithms](#FeatureExtractorandMachineLearningAlgorithms)
4. [Results](#Results)
6. [Authors](#authors)
 
 ## Introduction
 In this assignment, we apply SVM and RF algorithms to classify images
using features extracted through the SIFT technique. The objective is to eval-
uate the performance of both algorithms on image classification tasks and
compare their effectiveness. We also explore the preprocessing techniques used
to prepare the dataset for classification and evaluate their impact on the
classification results. The results of this study can provide insights into the
effectiveness of SVM and RF algorithms for image classification using SIFT
features and their potential applications in various domains.

## DataSet
For this project, two datasets are used. One conatined 64 images with 4 classes while second conatined 3670 images with 5 classes.

## Feature Extractor and Machine Learning Algorithms
We have used SIFT as feature extractor and used K-Means to cluster the similar features. SVM and Random forests are used for the classification. In the code you need to add the paths to the train and test image folder if dataset is already splitted other wise use DataSet 2 portion and just add the images folder path in it. You need to specify the images classes names, in the manner already defined in the code, in the variable class_indices. While i have used string processing to get the class name for each image using folder name, so set that according to the path settings. Another important thing to mention is that choose the value of K while calling create clusters function carefully, that can effect performance and efficiency as well.

## Results
Here are some snaps of the results that we got!
### Dataset 1
![image](https://user-images.githubusercontent.com/62650665/229735298-2a29c306-bd4b-4bdf-a55f-332974a09ca5.png)
![Screenshot from 2023-04-04 13-36-09](https://user-images.githubusercontent.com/62650665/229736247-f1bf27d0-05c2-4663-a0d9-53c5277c6ccd.png)
### Dataset 2
![Screenshot from 2023-04-04 13-36-26](https://user-images.githubusercontent.com/62650665/229736341-c420b52c-b5c9-42d5-a2ef-b3c314b1e4f9.png)
![Screenshot from 2023-04-04 13-36-34](https://user-images.githubusercontent.com/62650665/229736462-bbf4a249-1014-4020-b74c-4045304ebdf0.png)



## Authors
Israr Ahmed <iahmed.msds22seecs@seecs.edu.pk>

