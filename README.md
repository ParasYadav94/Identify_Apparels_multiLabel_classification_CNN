# Identify_Apparels_multiLabel_classification_CNN
More than 25% of entire revenue in E-Commerce is attributed to apparels &amp; accessories. A major problem they face is categorizing these apparels from just the images especially when the categories provided by the brands are inconsistent. This poses an interesting computer vision problem which has caught the eyes of several deep learning researchers.  Fashion MNIST is a drop-in replacement for the very well known, machine learning hello world - MNIST dataset which can be checked out at ‘Identify the digits’ practice problem. Instead of digits, the images show a type of apparel e.g. T-shirt, trousers, bag, etc. The dataset used in this problem was created by Zalando Research.

#Problem Statement
We have total 70,000 images (28 x 28), out of which 60,000 are part of train images with the label of the type of apparel (total classes: 10) and rest 10,000 images are unlabelled (known as test images).The task is to identify the type of apparel for all test images. Given below is the code description for each of the apparel class/label.

#Label	Description
0-T-shirt/top
1-Trouser
2-Pullover
3-Dress
4-Coat
5-Sandal
6-Shirt
7-Sneaker
8-Bag
9-Ankle boot  

#Public-Private Split
  Public and Private split for test images are 40:60.

#Evaluation Metric
  The evaluation metric for this challenge is multi-class accuracy.

#Data
  1) Train link has "train.csv" and apparel images for train
  2) Test link has "test.csv" having images name, need to predict the image label
  3) Sample Submissons link has the csv format for the submission file
