# Drug-Response-Prediction-for-Pancreatic-Cancer-using-Multiomics-profiling
Pancreatic cancer's challenges demand understanding drug responses. AI prediction improves outcomes, cuts costs. Integrating descriptors and cell features, this study achieves 89% accuracy with Tabnet. Identified common scaffolds for high IC50 drug clusters.
-
Pancreatic cancer poses a significant challenge due to its often late-stage diagnosis and limited treatment options. With its status as one of the deadliest cancers, there's a critical need to understand drug responses before recommending treatment for patients. AI-driven drug response prediction shows promise in personalizing treatment strategies, enhancing therapeutic outcomes, and reducing adverse effects and treatment costs. This research focuses on leveraging AI for predicting drug responses in pancreatic cancer. The study incorporates various drug descriptors and core structures (scaffolds) along with three cell line features: Chromatin Profiling, Reverse Phase Protein Array, and Metabolomics data. A feature-engineered dataset was constructed for drug response prediction, utilizing 53 unique drugs against 18 unique pancreatic cancer cell lines as the raw dataset. To manage the high dimensionality of the initial dataset, an ensemble method derived from five different techniques was employed for feature selection.

The dataset underwent evaluation with various computational learning models, achieving an accuracy of 89% using the Tabnet architecture. Additionally, the research identifies common scaffolds persistently found among drugs associated with high IC50-valued drug clusters.

Readme File:
Pancreatic Cancer Drug Response Prediction
Overview:
This repository contains code and data related to a research project on predicting drug responses in pancreatic cancer using AI-driven methods.

Contents:
**Data:
1. Copy of Datamol.ipynb - Processing drug data to get various chemical descriptors info using Datamol library. This code file also works on identifying scaffolds, common core structures
2. Feature_sSelection.ipynb - Contains how feature selection was done on the huge multiomics data., the ensemble method employed, visualization and Graphs
3. Pancan_tabnet.ipynb - Conatins the python execution file in complete { Kindly Note, there would lots of updates and you might find repeativity in blocks ., this is due to testing iterations )
4. panc_Can_prot.csv - Contains the preprocessed csv file to work
--**
Raw dataset comprising 53 unique drugs against 18 unique pancreatic cancer cell lines.
Additional datasets including drug descriptors, core structures (scaffolds), and cell line features (Chromatin Profiling, Reverse Phase Protein Array, Metabolomics data).
Code:
Feature engineering scripts for constructing the dataset.
Ensemble method for feature selection.
Implementation of computational learning models for drug response prediction.
Evaluation scripts for assessing model performance.
Results:

Performance metrics of various computational models evaluated on the dataset.
Identification of common scaffolds associated with high IC50-valued drug clusters.
Instructions:

Data Preparation:
Feature Engineering:
Execute feature engineering scripts to construct the dataset for drug response prediction.

Feature Selection:
Utilize the ensemble method for feature selection to manage high dimensionality.

Model Training and Evaluation:
Implement computational learning models (e.g., Tabnet architecture) for drug response prediction.
Evaluate model performance using provided evaluation scripts.

Results Analysis:
Analyze performance metrics and identify common scaffolds associated with high IC50-valued drug clusters.

Dependencies:
Python 3.x
Necessary Python libraries (e.g., scikit-learn, pandas, numpy)
Tabnet architecture (if using for model training)
