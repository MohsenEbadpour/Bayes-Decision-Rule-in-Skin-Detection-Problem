# Bayes Decision Rule in Skin Detection Problem
This repository contains code for a problem related to Bayes decision rule in pattern recognition. The problem involves Skin Detection task based on pixels value.

## Course Information

This problem is related to a *Statistical Pattern Recognition* course taught by Professor Mohammad Rahmati (<rahmati@aut.ac.ir>) in the Computer Engineering department at Amirkabir University of Technology (AUT) in Tehran, Iran. The course was offered in the Fall of 2021.

## Problem Description

This problem involves building a classifier for the Skin Detection problem using the Bayes decision rule. The Pratheepan dataset, consisting of 78 images, is used for this purpose. The dataset is divided into train and test sets, with the training images further divided into two subsets based on the complexity of the backgrounds. The ground truth for each image is stored separately as a binary image with white and black pixels representing 'skin' and 'non-skin', respectively. The first step is to find the class priors for the training set and report the prior probabilities for each class. Next, assuming a univariate Gaussian model for the class-conditional probability density, the mean and variance of both class-conditional densities need to be determined. Then, the pixels in two test images are classified using the trained classifier, and the results are displayed along with the ground truth. The classification is repeated using a MDC classifier, and the results are compared. The overall test error is reported, and a confusion matrix is computed for the classifier. The Bayes error is calculated, and a ROC curve is drawn to visualize the performance of the classification

![Out put](/output.png)


## Repository Contents

The repository contains Python code for the problem described above, as well as a Jupyter notebook that explains the problem in detail and provides a step-by-step cells for running the code.

## Feedback

If you have any feedback or suggestions for improving this code, please feel free to open an issue in the repository as well as send an email to Mohsen Ebadpour (<m.ebadpour@aut.ac.ir> , <mohsenebadpour@outlook.com>).
