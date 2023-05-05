## PROCESSAMENTO DE DADOS

- Ver se alguma das features tem valores nulos
- Eliminar as features que não interessam para o contexto do problema
- Analisar as instâncias de cada classe nos exemplos, e fazer oversampling das classes com menos exemplos (150000 exemplos)
- Heatmap e justificar se eleminamos mais alguma coisa ou não
- Feature Normalization

## VISUALIZAÇÃO DOS DADOS

- Histogramas/box plots

## MODEL TRAINING

- Split no train and test set
- Correr cada modelo uma vez no sklearn, ver a matriz de confusão
- Hyperparameter tuning com K-cross validation na classe GridSearchCV
- Para cada modelo, fazer novamente K-cross validation, com parâmetros ótimos
- Analisar matriz de confusão, F1 score e a curva ROC
	- Ver se melhoraram em relação ao passo anterior ao hyperparameter tuning
- Escolher melhores modelos e fazer a curva de validação


Modelos:
- Regressão logistica sem regularização
- Regressão logistica com regularização L1/L2
- SVM
- xgBoost
- Random Forest
- Neural Network