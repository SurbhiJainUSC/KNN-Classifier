# KNN-Classifier

The task is to classify patients in Vertebral Column dataset into one of the two categories: 
Normal (class 0) or Abnormal (class 1) using K-Nearest Neighbor Classification.

## Dataset
The Vertebral Column dataset consists data of 100 Normal patients and 210 Abnormal patients.
Each patient in the data set is represented by six biomechanical attributes derived from the shape 
and orientation of the pelvis and lumbar spine: pelvic incidence, pelvic tilt, lumbar lordosis angle,
sacral slope, pelvic radius and grade of spondylolisthesis. 

## Exploratory Data Analysis
Scatterplots between all the independent variables in the dataset and 
boxplots for each of the independent variables are used to analyze the data. 
The trainin set consists of first 70 rows of Class 0 and the first 140 rows of Class 1
and the rest of the data is used as testing set.

## Binary Classification
Following distance metrics have been used on the dataset to perform binary classification:
<li> Manhattan Distance
<li> Euclidean Distance
<li> Chebyshev Distance
<li> Mahalanobis Distance
<li> Minkowski Distance

All the distance metrics have been tested with two polling criteria:
<li> Majority Polling
<li> Weighted Polling
