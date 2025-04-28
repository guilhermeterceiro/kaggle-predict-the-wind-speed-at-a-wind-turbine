# kaggle-predict-the-wind-speed-at-a-wind-turbine
 Competitions

# Resumo

Este trabalho desenvolveu um modelo de regressão com o objetivo de prever a velocidade do vento em um aerogerador, utilizando apenas atributos de turbinas vizinhas. A aplicação prática do modelo visa possibilitar a identificação de falhas, a estimativa de geração durante períodos de interrupção de dados e a criação do input de modelos mais completos. Foi seguida uma abordagem estruturada de ciência de dados, compreendendo as etapas de definição do problema, análise exploratória, tratamento de dados ausentes, identificação e tratamento de outliers, normalização/padronização, engenharia e seleção de atributos, além da otimização de hiperparâmetros. Diversos modelos de aprendizado de máquina foram avaliados, como Linear Regression, Random Forest, XGBoost e LightGBM, utilizando o erro médio absoluto (MAE) como métrica de desempenho. Ao longo dos testes, melhorias sucessivas na qualidade das previsões foram obtidas por meio da seleção de atributos, inclusão criteriosa de dados ausentes, criação de variáveis temporais e angulares, e ajuste dos hiperparâmetros utilizando RandomizedSearchCV. O modelo XGBoost apresentou o melhor desempenho, atingindo um MAE de 0,293054, sendo validado também com o Teste de Kolmogorov-Smirnov, que confirmou, com p-valor inferior a 0,05, a superioridade estatística de sua distribuição de erros em relação aos demais modelos. Os resultados evidenciam o potencial de técnicas de aprendizado de máquina na previsão de variáveis meteorológicas e destacam a importância de um processo sistemático de pré-processamento e otimização na construção de modelos mais precisos.

Palavras-chave: Predição de vento, Ciência de Dados, Aprendizado de Máquina, MAE, Aerogeradores.


Nome da competição: Predict the wind speed at a wind turbine

https://www.kaggle.com/competitions/predict-the-wind-speed-at-a-wind-turbine/overview
