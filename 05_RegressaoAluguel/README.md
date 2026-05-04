# Rental Price Regression Analysis

Projeto de análise de dados e modelagem preditiva com o objetivo de estimar valores de aluguel de imóveis utilizando técnicas de regressão linear simples e múltipla.

Este projeto foi desenvolvido durante minha formação em Ciência de Dados na EBAC, com foco na aplicação prática de conceitos de pré-processamento, análise exploratória e modelagem estatística.

---

## Objetivo

Construir modelos capazes de prever o valor de aluguel com base em características dos imóveis, avaliando o desempenho de diferentes abordagens de regressão.

---

## Tecnologias utilizadas

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## Etapas do projeto

- Limpeza e preparação dos dados  
- Identificação e tratamento de outliers (método IQR)  
- Análise de correlação entre variáveis  
- Construção de modelo de regressão linear simples  
- Construção de modelo de regressão linear múltipla  
- Avaliação de desempenho utilizando R²  

---

## Resultados

### Regressão Linear Simples
- R² treino: **0.33**
- R² teste: **0.35**

### Regressão Linear Múltipla
- R² treino: **0.417**
- R² teste: **0.436**

---

## Análise dos resultados

O modelo de regressão múltipla apresentou melhor desempenho em comparação com o modelo simples, indicando que a inclusão de múltiplas variáveis melhora a capacidade preditiva.

Apesar disso, o ganho de performance foi moderado, sugerindo que:

- A variável **metragem** já possui forte influência no valor do aluguel  
- Algumas variáveis apresentam alta correlação entre si (multicolinearidade)  
- Fatores importantes como **localização** não estão presentes no dataset  

---

## Principais insights

- Existe uma relação positiva entre metragem e valor do aluguel  
- Imóveis com características semelhantes podem apresentar grande variação de preço  
- A inclusão de múltiplas variáveis melhora o modelo, mas não resolve totalmente a previsão  
- A qualidade e relevância das variáveis são fundamentais para modelos mais precisos  

---

## Possíveis melhorias

- Inclusão de variáveis como localização e padrão do imóvel  
- Aplicação de modelos mais avançados (Random Forest, XGBoost)  
- Engenharia de features  
- Normalização dos dados  

---

## Autor

Luiza Magnani  
Data Science Student
