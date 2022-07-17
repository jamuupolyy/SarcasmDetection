# Detecting sarcasm in online forum text using DistilBERT

--- 
Final group project was to investigate the effectiveness of pre-trained language models in detecting sarcasm using just sarcastic text. This was achieved by comparing conventional bag of words methods such as TF-IDF against contextual deep layer embeddings generated from Distilled BERT models. The embeddings harvested were used as input into standard classification models and a fine-tuned DistilBERT model was used as comparison.


---
## Running

We have not included the raw data in this repository as it would take up too much space. The data was sourced from https://www.kaggle.com/datasets/danofer/sarcasm.

The final results were generated using `DistilBERT_Fine_Tuning_Sentence_Classification_sarcasm.ipynb` located in `Jason`, using the parameters described in section 4 of our report `Final_Project_Report.pdf`.
