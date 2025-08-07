# Analise-Inadimplencia

Este projeto usa um conjunto de dados de crédito para prever a inadimplência de clientes usando machine learning, com foco em ajudar a tomada de decisão em empresas do setor financeiro.

## 🎯 Objetivo

Reduzir a inadimplência de 35% para 25% identificando clientes com maior risco antes da concessão de crédito.

## 📁 Conteúdo

- `modelo_inadiplencia.ipynb`: script principal com todo o pipeline.
- `csv_tratado.csv`: base de dados utilizada (dados simulados).
- `bancodados.sql`: base de dados não tratada(dados brutos).


## 🧪 Tecnologias
- SQL
- Python
- Pandas, NumPy
- scikit-learn
- RandomForestClassifier
- Matplotlib

## 🚀 Resultados

- Acurácia do modelo: **73%**
- Recall para inadimplentes: **88%**
- Modelo pode ser usado para reduzir a inadimplência com políticas baseadas em score de risco.

## 📈 Próximos passos

- Calibração de limiar de decisão
- Criação de um dashboard interativo com Power BI ou Streamlit
