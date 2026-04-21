# energy-consumption-analysis-maia

# Análise e Previsão de Consumo Energético - Município da Maia

Este projeto foi desenvolvido no âmbito da Unidade Curricular de **Introdução à Aprendizagem Automática** (2025/2026). O objetivo principal é aplicar a metodologia **CRISP-DM** para analisar padrões de consumo e prever a procura energética em edifícios municipais da Maia.

## 👥 Autores (Grupo LN3)
* Diogo Nunes
* Frederico Correia
* Pedro Vaz

## 📌 Descrição do Projeto
O projeto utiliza o conjunto de dados **D4Maia**, que contém aproximadamente 6 milhões de registos de leituras de energia (potência ativa, reativa e temporal) recolhidas a cada 15 minutos.

A análise divide-se em duas vertentes principais:
1. **Aprendizagem Não Supervisionada:** Utilização de algoritmos como **K-Means** e **DBSCAN** para identificar perfis de consumo e detetar outliers.
2. **Aprendizagem Supervisionada:** Implementação de modelos para previsão de consumo a curto prazo (uma semana), comparando abordagens de séries temporais (**ARIMA**, **LSTM**) com modelos de regressão (**Random Forest**, **XGBoost**, **MLP**).

## 🚀 Metodologia
Seguimos o processo **CRISP-DM**:
- **Compreensão do Negócio e Dados:** Análise exploratória e estatística.
- **Preparação de Dados:** Limpeza, normalização e engenharia de características (feature engineering).
- **Modelação:** Aplicação de modelos de clustering e previsão.
- **Avaliação:** Comparação de métricas face a uma *baseline* (consumo da semana anterior).

## 🛠️ Tecnologias Utilizadas
- Python
- Pandas / NumPy (Processamento de dados)
- Scikit-Learn / XGBoost (Modelos de ML)
- Matplotlib / Seaborn (Visualização)

## 📁 Estrutura do Repositório
- `projeto_final.ipynb`: Jupyter Notebook com toda a implementação e análise.
- `data/`: Dataset D4Maia.

## 📊 Resultados
Os modelos foram validados contra uma baseline simples. Os resultados demonstram a capacidade das técnicas de Machine Learning em capturar a variabilidade do consumo municipal e identificar comportamentos distintos entre diferentes locais de entrega (CPEs).
