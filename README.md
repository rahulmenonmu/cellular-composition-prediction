# Histology image cellular composition prediction

Regression Models for prediction of cellular composition from histological image patches

## Overview

In this project, the objective is to develop regression models for predicting the number of six different types of cells in a given histological image patch. The task is to develop a machine learning model that uses training data (patch images with given cell counts) to predict cell counts of each type in test images. Counts of different types of cells in a given image patch is called its cellular composition.


### Data
Colon Nuclei Identification and Counting Challenge (see: https://github.com/TissueImageAnalytics/CoNIC and https://arxiv.org/abs/2111.14485 for details about the challenge). 
The data files required for this project (counts.csv, images.npy) can be downloaded from: http://shorturl.at/fsGNU. This link also contains other files including a readme and binding licensing information for this dataset.
The split file split.tx is available in this repository
The data in split.txt consists of 3 folds. Here, X is a matrix containing N 256x256x3 Red-GreenBlue (RGB) channel images of size 256x256 pixels and Y is an Nx6 matrix with each row corresponding to a single image patch and each column corresponding to the 6 cell types (called T1: neutrophil , T2: epithelial T3: lymphocyte, T4: plasma , T5: eosinophil and T6: connective). Thus, for a single image, you are given the counts of each of the six cell types.

