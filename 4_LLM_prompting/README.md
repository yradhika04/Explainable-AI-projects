# Project 4-  Multimodal Task with Prompting Large Language Models


## Project Description 

Choose a multimodal task (VQA-X, E-SNLI-VE, A-OKVQA or VCR), select 100 samples from any split of the dataset. If image captions are not available generate them. Prompt a large language model (LLM) to solve the task and to generate rationales. 

## Data Description
**Name:**  A-OKVQA  <br>
**Available in:** https://allenai.org/project/a-okvqa/home <br>
**Characteristics:** Consists of almost 24, 903 samples with question/answer/rationale triplets. The main characteristic of these questions is that they cannot be answered by simply querying a knowledge base some sort of commonsense reasoning about the image scene is needed.<br>


## Task 

**Visual Question Answering (VQA):** consists of answering open-ended questions about an image.<br>
* For this task we used the validation set and we added the images as well as image captions from the COCO dataset. 


# Models

* Flan-T5 - Large for prompting answers and explanations.<br>


## General Organization 
1) ***Code Folder:***  
    1.1) **Data Folder:** includes the A-OKVQA validation set (aokvqa_v1p0_val.json) and the captions validation set (captions_val2017.json) from COCO datset as JSON files. 
    1.2) *Project4.ipynb:* Notebook with data preprocessing and large language model prompting.<br>

2) ***Tables Folder:*** includes: 
    * annotations_radhika.xlsx: manually annotated samples by Radhika. <br>
    * annotations_valentina.xlsx: manually annotated samples by Valentina. <br>
    * answers_and_explanations.csv: file with image ids, true answers, predicted answer true ratonales and predicted rationales. <br>
    * final_scores.csv: METEOR and Sacre BLEU scores for both predicted answers and explanations and inter-annotator agreement scores for goodness and satisfaction. <br>

4) *Requirements.txt:* includes all the requirements for running the code successfully. 


## Authors 

Radhika Yadav and Valentina Tretti 


## References 
Lewis, P., Oğuz, B., Rinott, R., Riedel, S., & Schwenk, H. (2019). MLQA: Evaluating Cross-lingual Extractive Question Answering. ArXiv. 
https://doi.org/10.48550/arXiv.2206.01718


Tsung-Yi Lin, Maire, M., Belongie, S. J., Bourdev, L. D., Girshick, R. B., Hays, J., … Zitnick, C. L. (2014). Microsoft COCO: Common Objects in Context. CoRR, abs/1405.0312. https://doi.org/10.48550/arXiv.1405.0312

