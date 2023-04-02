### mappshow - medical appointment show up prediction


#### Data
The dataset analyzed in this project contains 110527 records of medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment.

The dataset is available on [Kaggle](https://www.kaggle.com/joniarroba/noshowappointments).

The dataset is preprocessed using `dataset_prep_eda.ipynb` notebook and stored in the `data` folder.


#### Problem Statement
The aim of this project is to prepare a model that predicts whether or not a patient will show up for their scheduled appointment. The model decision should be explainable and should be able to predict the probability of a patient showing up for their appointment.


#### Machine Learning and Explainable AI
The machine learning and XAI part of the project is implemented in `classifiers_xai.ipynb` notebook.

### Environment Setup

Using conda environment:

    conda env create -f env.yml
    conda activate mappshow