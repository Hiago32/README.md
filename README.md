# Projeto Final de Análise de Dados e Machine Learning — Dataset Iris

## 1. Problemática

O objetivo deste projeto é classificar a espécie da flor Iris com base em medidas das pétalas e sépalas. Esta é uma tarefa clássica de aprendizado de máquina de classificação, onde a identificação correta da espécie pode ajudar em estudos botânicos e aplicações agrícolas.

## 2. Coleta e Preparação dos Dados

Utilizamos o dataset Iris disponibilizado pela biblioteca scikit-learn, que contém 150 amostras de três espécies de Iris: Setosa, Versicolor e Virginica, com quatro características numéricas.

Os dados foram carregados diretamente da biblioteca, e submetidos a limpeza mínima, pois o dataset já está estruturado.

## 3. Análise Exploratória dos Dados

Foi realizada uma análise descritiva inicial para entender a distribuição das variáveis, além de gráficos como pairplot para visualizar a relação entre as features e a separação das espécies.

A correlação entre as variáveis foi analisada, indicando que comprimento e largura das pétalas são as características mais importantes para diferenciar as espécies.

## 4. Modelagem

Foi escolhido o modelo Random Forest por sua capacidade de lidar bem com dados numéricos e multiclasses, além da facilidade de interpretação da importância das variáveis.

Os dados foram divididos em conjuntos de treino e teste com estratificação, e escalonados para melhor desempenho do modelo.

## 5. Avaliação do Modelo

O modelo apresentou alta acurácia (superior a 90%) na classificação das espécies no conjunto de teste.

Foram apresentadas métricas como matriz de confusão e relatório de classificação para detalhar o desempenho.

## 6. Conclusões

- O Random Forest classificou com alta precisão as espécies de Iris.  
- As medidas das pétalas são determinantes para a classificação.  
- O projeto demonstra a importância da análise exploratória para guiar as escolhas de modelagem.  
- Próximos passos incluem testar outros modelos e otimizar hiperparâmetros.

---

**Autor:** Alex 
**Data:** 2025-12-11
