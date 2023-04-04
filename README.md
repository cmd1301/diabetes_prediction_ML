# Diabetes Prediction Project using Machine Learning

O projeto "Predição de Diabetes Usando Machine Learning" tem como objetivo prever se um paciente terá ou não diabetes com base em seus dados de saúde. 
Utilizando um dataset obtido no Kaggle, foi realizada a análise exploratória dos dados, limpeza, teste de modelos de machine learning com otimização de hiperparâmetros escolhidos. 
Foram testados quatro modelos de classificação: Regressão Logística, K-Nearest Neighbor, Decision Tree e Random Forest.

Os resultados foram avaliados com base na métrica "recall", que representa a capacidade do modelo em identificar corretamente os casos positivos e diminuir os casos de falso negativos. 
Os modelos que mais se aproximaram em valor de acurácia foram regressão logística e random forest, no entanto, os valores ainda são inferiores aos encontrados na referência. 
O modelo com maior valor absoluto de recall foi o random forest, porém,nenhum dos modelos testados está apto para aplicação na produção, já que os resultados obtidos não foram suficientemente precisos para um diagnóstico de saúde.
