# Project 3- Multimodal Task and Feature Attribution 


## Project Description 

Use a multimodal dataset (image-text),  extract features: visual and textual from pre-trained models and implement a XGBoost model. 

## Data Description
**Name:** Fashion Product Images Dataset <br>
**Available in:** https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-dataset<br>
**Characteristics:** Consists of image-text pairs regarding fashion products. For this project only 2000 samples were considered.<br>


## Task 

**Binary classification:** classification of image-text pairs into two gender classes (man/0 and woman/1). t<br>
**Class distribution:** 0 (56.8%) + 1 (43.2%) in dataset.<br>

# Models

**Feature Extraction:**
* Visual features: A fine-tuned version of DeBERTa (clothing_subcategory_classifier)<br>
* Textual features: A fine-tuned Vision Transformer (ViT) model (vit-base-clothing-leafs-example-full-simple_highres)<br>


**Classification task:**
* XGBoost Model<br>


## General Organization 
1) ***Code Folder:***  
    1.1) **feature_arrays folder:** includes all csv files with data and new features for running the code. <br>
    1.2) *Project3FashionFeatures.ipynb:* Notebook with data preprocessing and feature extraction (visual and textual) from pre-trained models.<br>
    1.3) *Project3XGVBoostipynb.ipynb:* Notebook with the XGBoost model with text and image features.<br>

2) ***Figures Folder:***  
Includes the visualizations: confusion matrix, decision tree, feature importance (sorted and from XGBoost).<br>

3) ***Tables Folder:*** 
Includes the evaluation results file.<br>

4) *Requirements.txt:* includes all the requirements for running the code successfully. 


## Authors 

Radhika Yadav and Valentina Tretti 




