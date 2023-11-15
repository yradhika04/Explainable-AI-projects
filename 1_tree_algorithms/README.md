# Project 1: Tree Algorithms - Decision Trees or Random Forests

## Project Description 
Implement a tree algorithm on a selected data set, perform hyperparameter search, and feature importance analysis. 


## Data Description 
**Name:** Stellar Classification Dataset - SDSS17 dataset. <br>
**Authors:** released by Sloan Digital Sky Survey under public domain.  <br>
**Available in:** https://www.kaggle.com/fedesoriano/stellar-classification-dataset-sdss17. 
**Brief Description:**
The dataset is formed of 100,000 rows and 18 columns, 17 represent a feature (obj_ID, alpha, delta, u, g, r, i, z, run_ID, rerun_ID, cam_col, field_ID, spec_obj_ID, redshift, plate, MJD, fiber_ID) and 1 the label (class). 

## Task
**Stellar Classification:** a classification of stars based on some spectral characteristics. The aim of the dataset is to classify the galaxies, quasars, and stars based on different features. 


## General Organization
1) **tables folder:**  
Includes the result tables (accuracy, f1-score, recall, precision). <br>

2) **figures folder:** 
Includes the visualizations (confusion matrix, feature importance, decision trees, and correctly and incorrectly classified examples).<br>

3) **code Folder:** <br>
Includes the data exploration and the models. <br>

    * 3.1)**data_exploration:** <br>
        Notebook for data exploration and division of the original dataset into training and testing datasets.<br> 

    * 3.2)**stars_classification:** <br>
        Includes the implementation of all the decision tree models and their optimizations. <br>

4) **Requirements.txt:** includes all the requirements for running the code successfully. 


## Authors 
Radhika Yadav
Valentina Tretti


## References 
Fedesoriano. (January 2022). Stellar Classification Dataset – SDSS17. Retrieved [May, 2023] from https://www.kaggle.com/datasets/fedesoriano/stellar-classification-dataset-sdss17
