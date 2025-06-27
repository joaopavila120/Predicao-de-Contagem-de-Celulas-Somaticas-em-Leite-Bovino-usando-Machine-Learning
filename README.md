# Uso de técnicas de Machine Learning na análise da relação da composição do leite bovinocom a contagem de células somáticas
Este projeto aplica técnicas de Machine Learning para prever a contagem de células somáticas (CCS) em amostras de leite bovino, analisando a relação entre lactose, gordura e proteína — principais indicadores da saúde do úbere das vacas leiteiras. Desenvolvido como Trabalho de Conclusão de Curso (TCC) em Ciência da Computação pela UPF.


##  Objetivo

- Construir modelos de Regressão Linear, Random Forest e XGBoost para prever CCS a partir de dados de composição do leite.
- Avaliar o desempenho dos modelos com métricas como R² e MSE.
- Interpretar os modelos com SHAP, destacando as variáveis mais importantes para predição.

- ## 📊 Técnicas utilizadas

- **Machine Learning**:
  - Regressão Linear Simples e Múltipla (statsmodels).
  - Random Forest Regressor (scikit-learn).
  - XGBoost Regressor (XGBoost + SHAP).

- **Análises Estatísticas**:
  - Correlação de Pearson e Spearman.
  - Análise de distribuição de variáveis.

- **Visualização**:
  - Matplotlib e Seaborn para gráficos de boxplot, histogramas e beeswarm SHAP.

## 🔍 Resultados principais

- A lactose foi o preditor mais importante da CCS, com correlação negativa moderada (r=-0.37) e maior importância nos modelos Random Forest e XGBoost.
- Modelos não-lineares (Random Forest e XGBoost) apresentaram desempenho R² ≈ 0.175, capturando parcialmente a complexidade do fenômeno.
- SHAP revelou como alterações na lactose influenciam diretamente a previsão da CCS, proporcionando interpretabilidade para decisões práticas.

- ## 🛠️ Tecnologias

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- SHAP
- Matplotlib & Seaborn
- Google Colab

## 👨‍💻 Autor

João Paulo de Avila – Ciência da Computação – UPF

## 📄 Licença

[MIT License](LICENSE)
