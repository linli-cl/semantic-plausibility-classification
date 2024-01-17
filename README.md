# HuMiLity - Modeling Semantic Plausibility

This repository contains the code for data analysis as well as code for modeling semantic plausibility in winter 2023/2024 by Huirong Tan, Miriam Segiet, and Li Lin.

> When you need to setup a new environment, use `pip install -m requirements.txt` to load the required packages stored in the corresponding file. If not already satisfied, make sure to download the tagger part of the nltk library by using `nltk.download('averaged_perceptron_tagger')`.

The whole analysis and classification based on the pep-3k dataset is included in the folder `pep-3k_classification`. 
This folder contains three separate files:
* pep3k_data_analysis.py which contains the analysis of the pap-3k dataset
* pep3k_keras.py which contains a classification model based on keras and additional training data from pap
* pep3k_evaluation.py which contains the evaluation based on precision, recall, f1 score, and roc auc scores


### Data_analysis folder contains these files:

* data_analysis_compare.py: for pap and pep-3k dataset analysis.
* data_analysis_pap_abstractness.py: for abstractness analysis of pap dataset.
* demo_display.ipynb: the display of partial analysis results on pap and pep-3k datasets. To run the code in it, the data location is in: Modeling_Semantic_Plausibility/Data/pap, Modeling_Semantic_Plausibility/Data/pep-3k. 
* pap analysis_WordFreq_AnnoDiff.ipynb: for pap analysis of Word Frequency Distribution and Annotation Difference.

### pap_roberta folder contains:

* pap_roberta.ipynb: model training based on Roberta with pap and extra training data from pep3k; model evaluation.




