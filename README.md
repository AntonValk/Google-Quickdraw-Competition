# Google-Quickdraw-Competition
Group work on Google's Quickdraw competition. The actual challenge is harder since we used a subset of the complete dataset and added noise to the images.


## Team Name: Artificial-Stupidity

### Authors: Antonios Valkanas, Ali Shobeiri, Elie-Joe Haykal

This repo contains our team submission to: https://www.kaggle.com/c/f2018-hand-drawn-pictures
Technologies used: SciKit Learn, OpenCV, Keras

OpenCV was used primarily to reduce image noise
SciKit Learn was used to fit linear baselines to measure performance
Keras was used to apply Deep Learning to the denoised images for classification
File Breakdown

KaggleProject.ipynb: Contains our best performing deep learning model as well data preprocessing steps to reduce image noise.

Neural-Network.ipynb: Contains a hand implemented fully connected feed forward neural network that is used to classify images.

Linear-SVM.ipynb: Contains benchmarking used to determine performance of preprocessing and give baselines to compare our deep learning solutions to.
