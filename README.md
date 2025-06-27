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

**Use of Machine Learning Techniques in the Analysis of the Relationship Between Bovine Milk Composition and Somatic Cell Count**
This project applies Machine Learning techniques to predict the somatic cell count (SCC) in bovine milk samples by analyzing the relationship between lactose, fat, and protein — key indicators of the udder health of dairy cows. Developed as a Computer Science Undergraduate Thesis (TCC) at UPF.

🎯 Objective
Build Linear Regression, Random Forest, and XGBoost models to predict SCC based on milk composition data.

Evaluate model performance using metrics such as R² and MSE.

Interpret the models with SHAP, highlighting the most important variables for prediction.

📊 Techniques Used
Machine Learning:

Simple and Multiple Linear Regression (statsmodels).

Random Forest Regressor (scikit-learn).

XGBoost Regressor (XGBoost + SHAP).

Statistical Analyses:

Pearson and Spearman correlation.

Analysis of variable distributions.

Visualization:

Matplotlib and Seaborn for boxplots, histograms, and SHAP beeswarm plots.

🔍 Main Results
Lactose was the most important predictor of SCC, showing a moderate negative correlation (r=-0.37) and the highest importance in the Random Forest and XGBoost models.

Non-linear models (Random Forest and XGBoost) achieved R² ≈ 0.175, partially capturing the complexity of the phenomenon.

SHAP revealed how variations in lactose directly influence SCC predictions, providing interpretability for practical decision-making.

🛠️ Technologies
Python 3.x

Pandas

NumPy

Scikit-learn

XGBoost

SHAP

Matplotlib & Seaborn

Google Colab

## 👨‍💻 Autor

João Paulo de Avila – Ciência da Computação – UPF

## 📄 Licença

[MIT License](LICENSE)
