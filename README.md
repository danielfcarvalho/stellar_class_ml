## Context

The goal of this project, done for the subject Tópicos de Aprendizagem Automática at Universidade de Aveiro, was to train various supervised machine learning (ML) models to classify instances from the Sloan Digital Sky Survey Data Release 17 (SDSS DR17) as either Galaxies, Stars or Quasars. The goal was to select models already testes in related work, as well as to train new models not used before on this problem, and then compare their results in terms of efficiency and accuracy, based on various performance metrics. Hyper-parameter tuning was also applied, to check whether this had any effect in improving the efficiency of the tested models.

## Trained Models

The trained models included:
- Logistic Regression (with/withotu regularization)
- Support Vector Machine
- XG Boost
- Random Forest
- Neural Network

## Results

In brief, all of the models obtained positive values for the performance metrics used, with balanced accuracies of over 94% after hyper-parameter tuning. The best performing models were Random Forest and XG Boost, with balanced accuracies of 97% and Precision, Recall and F1-Scores above 96%. 
A full description of the results is present in the report, provided in the reports folder.

## Development Team

- [Artur Correia](https://github.com/afarturc) (art.afo@ua.pt)
- [Daniel Carvalho](https://github.com/danielfcarvalho) (dl.carvalho@ua.pt)
