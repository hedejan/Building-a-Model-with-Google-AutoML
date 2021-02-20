# Building-a-Model-with-Google-AutoML
Udacity - AI for Business - P2

## Project Overview
In the previous project, you created the instructions needed to build a labeled dataset that distinguishes between healthy and pneumonia x-ray images. This dataset would eventually be used to build a product that helps doctors quickly identify cases of pneumonia in children. Remember that the goals of this product are to:
* help flag serious cases,
* quickly identify healthy cases,
* and, generally, act as a diagnostic aid for doctors.

## The Data
We'll be using the same Kaggle chest x-ray dataset that we used in the previous project, except here, we'll skip the step of using Figure Eight's platform to label the data, and just use the original labels supplied with the data on Kaggle.

## The Four Parts of the Project
We will train four different models using four variants of the pneumonia dataset. Recall that the dataset contains childrens' chest x-ray images, and that they are classified into two classes, "normal" and "pneumonia". The following sections describe the steps you must take to create each model.
1. Create a binary classifier to detect pneumonia using chest x-rays
2. Create an unbalanced binary classifier
3. Create a binary classifier with dirty data
4. Create a three-class model with the classes “normal”, “bacterial pneumonia”, and “viral pneumonia”
