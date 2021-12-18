---
title: "Buzz Receiving and Responding: Intelligent Report Classification Model"
date: 2021-02-07T17:23:18.431Z
summary: An intelligent system to report and predict the Vespa mandarinia based
  on mathematic modeling and machine learning.
draft: false
featured: false
authors:
  - Zihao Wei
links:
  - name: ""
    url: https://github.com/Zi-hao-Wei/MCM2021-C
    icon_pack: fab
image:
  filename: buzz.png
  focal_point: Smart
  preview_only: false
---
Much attention has been attracted to Vespa mandarinia since they are first spotted in the USA in 2019. As the most savage alien insects, they pose a great threat to local agriculture and citizens’ life. The State of Washington has encouraged the public to report sightings of these giant hornets while the correctness of reporting remains to be improved. In this paper, we construct an intelligent report classification model based on automatic interpretation of reported files.

First, as the premise of the model, we discuss the predictability of the spread of Asian giant hornets over time. Apart from proof from biology documents and existing models, we construct Scoring Probability Model (SPM) based on distance and number of sightings to testify that the spread is predictable. Level of precision is then calculated by estimating positive sightings among the unverified reports. The result is as low as 22.22%, which calls for further improvement.

Second, Computer Vision Process is operated on the data. We conduct data cleaning to the videos by intercepting the picture on each frame. Though the scale of given photos is highly limited, we extract the potential information to the fullest. Around 1100 photos are classified to "Hornet-Like" and "Not-Hornet" and over 600 photos are labelled by hand.After that, LeNet framework Convolutional Neural Networks (CNN) is utilized to operate Similarity Matching, then the result would be the similarity value. We then employ YOLOv3 to do object extraction algorithm to examine the quality of a photo. Both similarity value and quality of a photo constitute the score from image. 

Third, we conduct Natural Language Process to the notes. After stemming and lemmatization, words are transformed to vectors by Word2vec. Similarity Matching can thus be operated. We then combine Characteristic Words Analysis and Sentimental Analysis by constructing professional word set to quantitively interpret the sentences. The results of all three techniques make up the score from text. 

Our intelligent report classification model is finally built based on those two scores in combination with distance and time. The weight of each parameter is determined by Analytic Hierarchy Process (AHP). We calculate the accuracy of the likelihood of a mistaken classification as 60% and prioritize the submitted reports. 

As complement to the model, we determine the method and period of update taking hornets reproduction model and citizens’ habits into consideration. We thus build a detailed update pattern and a dynamic update period system based on Difference Equation Model (DEM) and public report submission frequency. Indication of the hornets eradication is provided as well. 

In conclusion, we build a intelligent report classification model by computer vision and natural language processing techniques. A complete update pattern and dynamic update period are given too. The classification model could predict the likelihood of a wrong classification within acceptable accuracy and prioritize the possible positive reports with high precision. The entire system could be used to enhance the prevention and control of the spread of Asian giant hornets in Washington.