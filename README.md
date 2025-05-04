# Análise de Fatores de Risco de Ataque Cardíaco

Este projeto utiliza um banco de dados sintético retirado da plataforma Kaggle, com dados sobre fatores de risco de ataque cardíaco. A análise incluiu variáveis demográficas, históricas e de estilo de vida, com foco na identificação de fatores-chave associados à incidência de ataque cardíaco.

## Objetivos
- Analisar os principais fatores de risco de ataque cardíaco.
- Criar e avaliar modelos preditivos.

## Métodos
- Análise descritiva, univariada e bivariada.
- Matriz de correlação e análise de multicolinearidade.
- Treinamento de três modelos preditivos com diferentes variáveis:
  - Modelo 1: 18 variáveis.
  - Modelo 2: 8 variáveis (p-value < 5%).
  - Modelo 3: 3 variáveis principais de uma árvore de decisão.
  
## Modelo Escolhido
O Modelo 2, com 8 variáveis, apresentou os melhores resultados:
- Acurácia (teste): 87,7%.
- AUC (teste): 95,5%.
- GINI (teste): 91,1%.
- KS (teste): 75,3%.
- Recall: 91.1%

## Conclusões
Os principais fatores associados ao ataque cardíaco incluem:
- Idade avançada, hipertensão, colesterol elevado, tabagismo, obesidade e histórico familiar.
  
O modelo de regressão logística desenvolvido mostrou-se eficaz e pode ser utilizado para auxiliar na prevenção precoce.

## Requisitos
- Bibliotecas: pandas, numpy, scikit-learn, matplotlib, seaborn, statsmodels e spicy.
