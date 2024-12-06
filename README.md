# kaggle-predict-the-wind-speed-at-a-wind-turbine
 Competitions

# 1. Definição do Problema

## a) Apresentação dos dados públicos utilizados
Os dados representam a operação de um parque eólico (usina) que possui 6 turbinas. Para cada turbina tem um total de 10 categorias, por exemplo, velocidade e direção do vento, rotação e potência gerada do aerogerador, direção da nacele e posição da pá. No entanto, os dados de uma turbina foram retirados do dataset e a velocidade do vento nessa turbina ficou como target desse problema de machine learning.

Os dados são médias a cada 10 minutos de medições realizadas a cada segundo. Total de 144 linhas por dia. Para realizar os teste no modelo, a cada 2 semanas de dados destinado para o dataset de treino 1 semana foi destinada para o dataset de teste.

## b) Descrevendo a problemática
O orgão do governo que supervisiona a operação de usinas de energia penaliza os proprietário/acionista do empreendimento quando o parque não produz o que foi definido no contrato. Quando uma turbina sofre uma falha ou tem sua operação interrompida para manutenções preventivas, os orgão param de receber os dados dessa turbina e podem cobrar multa sobre essa interrupção de acorodo com modelos que preditam a potência que está sendo perdida com a máquina parada. O modelo desse trabalho predente estimar a velocidade do vento nessa máquina que hipotéticamente está fora operação com o objetivo tornar o valor da multa mais justa e real possível, indicando a velocidade do vento que estaria presente na turbina se ela tivesse em operação.

Resumindo, não temos os dados dessa turbina, apenas das 5 vizinhas. Com os dados das demais precisamos estimar a velocidade do vendo na turbina que não está operando. Apesar de termos uma série temporal, o problema é de REGRESSÃO.

## c) Origem dos dados
Os dados foram baixados da plataforma Kaggle de uma competição ativa no formato csv.

Nome da competição: Predict the wind speed at a wind turbine

https://www.kaggle.com/competitions/predict-the-wind-speed-at-a-wind-turbine/overview
