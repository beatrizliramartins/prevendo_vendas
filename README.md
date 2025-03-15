# 📈 Prevendo Vendas com CatBoost  

## 🚀 Visão Geral  
Este notebook usa aprendizado de máquina para prever vendas, utilizando o modelo **CatBoost** e explorando séries temporais.  

## 🛠️ Bibliotecas Utilizadas  
- `pandas` e `numpy` → Manipulação de dados  
- `matplotlib` e `seaborn` → Visualizações  
- `scikit-learn` → Pré-processamento e divisão de dados  
- `catboost` → Modelo de Machine Learning  
- `shap` → Interpretação dos resultados  

## 📥 Importação e Tratamento de Dados  
- Carrega o dataset `Previsão de Vendas.csv`.  
- Converte a coluna de datas (`Data`) para formato datetime.  
- Exibe informações básicas e trata valores nulos.  

## 📊 Análise e Transformações  
- Normaliza os dados com `StandardScaler`.  
- Aplica `KMeans` para identificar padrões nos dados.  
- Utiliza `boxcox` para ajustar distribuições.  

## 🤖 Modelo de Machine Learning  
- Usa `CatBoostRegressor` para prever vendas.  
- Aplica `TimeSeriesSplit` para garantir que os dados sejam divididos corretamente.  
- Interpreta o modelo com `SHAP`.  

🔥 **O resultado? Um modelo eficiente para prever vendas e ajudar na tomada de decisões!**  

