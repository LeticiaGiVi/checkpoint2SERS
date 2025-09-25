# checkpoint2SERS
*Feito por: Leticia, Livia, Luize e Sarah - 1CCR*

Exercício 1 - Classificação (Solar)

Título: Previsão de nível de radiação solar

Objetivo: Desenvolver um modelo supervisionado para classificar períodos em Alta Radiação e Baixa Radiação solar utilizando dados do dataset Solar Radiation Prediction.

Dataset: Solar Radiation Prediction Dataset - Kaggle

Metodologia:

    Criação da variável-alvo baseada na mediana da radiação

    Comparação de três algoritmos:

        Árvore de Decisão

        Random Forest

        Support Vector Machine (SVM)

    Divisão dos dados: 70% treino / 30% teste

    Normalização dos atributos contínuos

    Métricas de avaliação: Acurácia e Matriz de Confusão

Exercício 2 - Regressão (Eólica)

Título: Previsão de potência de turbinas eólicas

Objetivo: Desenvolver modelos de regressão para prever a potência gerada (kW) por turbinas eólicas baseando-se em dados operacionais.

Dataset: Wind Turbine Scada Dataset - Kaggle

Metodologia:

    Comparação de três algoritmos:

        Regressão Linear

        Regressão de Árvores

        Random Forest Regressor

    Divisão dos dados: 80% treino / 20% teste

    Normalização dos dados

    Métricas de avaliação: RMSE e R²


Resultados Principais
Exercício 1 - Classificação Solar

    -Melhor algoritmo: Árvore de Decisão e Random Forest

    -Acurácia: 100%

Exercício 2 - Regressão Eólica

    -Melhor algoritmo: Regresão Linear

    -RMSE: 411.71

    -R²: 0.90
