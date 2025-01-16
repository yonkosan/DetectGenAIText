# DETECTING AI GENERATED TEXT
## Overview
This projects implements a pipeline to analyze and classify text data, distinguishing between student essays and AI-generated essays. The code combines exploratory data analysis, text processing, and machine learning to achieve its goal.

## Dataset
* A combination of two dataset has been used which contain the list of student generates essays and AI generates essays.
* Datasets are extracted from :
    * https://www.kaggle.com/datasets/nbroad/daigt-data-llama-70b-and-falcon180b
    * https://www.kaggle.com/datasets/thedrcat/daigt-v2-train-dataset

* Extract theser datasets and save them under the folder "kaggle/input"
* under the name "llama_falcon_v3.csv" and "train_v2_drcat_02.csv"

## Usage
* clone the repo
* Prepare the dataset
* Run the script to train the model
* change the test dataset to your dataset folder
* Run the script to evaluate on new data

## Dependencies
- Python 3.7+
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn
- tokenizers
- transformers
- tqdm
- datasets



