# Project 2 - Language Task & Feature Attribution Analysis


## Project Description 

Implement a classification/regression pre-trained transformer architecture with a dataset that is based on a language task. 


## Data Description
**Name:** MLQA (a multi way aligned extractive QA evaluation benchmark).<br>
**Authors:** Lewis, P., Oğuz, B., Rinott, R., Riedel, S., & Schwenk, H. (2019)<br>
**Available in:** https://github.com/facebookresearch/mlqa<br>
**Characteristics:** Consists of over 5K extractive QA instances (12K in English) in SQuAD format in seven languages ( English, Arabic, German, Spanish, Hindi, Vietnamese and Simplified Chinese ). The number of instances for English language are: 1148 for developing set and 11590 testing set.<br>


## Task 

**Span-based QA:** is a task where you have two texts, one called the context, and another called the question. The goal is to extract the answer of the question in the text, if it exists. 

# Model 

**DistilBERT:** has the same general architecture as BERT. The token- type embeddings and the pooler are removed while the number of layers is reduced by a factor of 2. Its faster and smaller than BERT. 

Developed by: Sanh, V., Debut, L., Chaumond, J. & Wolf, T. (2019).

## General Organization 
1) ***Tables Folder:***  
Includes the result tables (f1-score, exact match, METEOR, BLUE, SQUAD, Google-Blue). <br>

2) ***ShapPlots Folder:***  
Includes the visualizations - SHAP htmls.<br>

3) ***BarPlots Folder:*** 
Includes the bar plots for the top 20 start and end word scores for sample example. 

4) ***Code Folder:*** <br>
Includes the training with selected data set of DistilBERT model and the evaluation and explainability of the model. <br>

    * 4.1)**DiffModelTrain:** <br>
        Notebook for training the model with selected MLQA dataset and saving it.<br> 

    * 4.2)**DiffModelEvaluate:** <br>
        Includes the implementation the DistilBERT model, evaluation and the SHAP plots generations for explainability. <br>

5) Requirements.txt: includes all the requirements for running the code successfully. 


## Authors 

Valentina Tretti and Radhika Yadav

# References
Chen, A., Stanovsky, G., Singh, S., & Gardner, M. (2019). Evaluating Question Answering Evaluation. Conference on Empirical Methods in Natural Language Processing.

Lewis, P., Oğuz, B., Rinott, R., Riedel, S., & Schwenk, H. (2019). MLQA: Evaluating Cross-lingual Extractive Question Answering. ArXiv, abs/1910.07475.

Sanh, V., Debut, L., Chaumond, J. & Wolf, T. (2019). DistilBERT, a distilled version of BERT: smaller, faster, cheaper and lighter. arXiv preprint arXiv:1910.01108.







