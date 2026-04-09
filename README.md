# Previsão de Doenças Cardiovasculares com Regressão Logística + IMC

**Projeto de Ciência de Dados | Módulo 27**

Modelo de **Regressão Logística** para prever o risco de doenças cardiovasculares utilizando dados reais de pacientes.

## 🎯 Objetivo
Desenvolver um modelo de classificação binária capaz de identificar pacientes com maior probabilidade de desenvolver doenças cardiovasculares.

## 🛠️ Tecnologias Utilizadas
- Python
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Regressão Logística

## ✨ Principais Features
- Análise exploratória completa (univariada + bivariada)
- Criação da feature **IMC** (Índice de Massa Corporal) — variável clínica essencial
- Tratamento de outliers
- Padronização dos dados
- Balanceamento com SMOTE
- Avaliação completa do modelo (acurácia, recall, AUC-ROC)
- Interpretação dos coeficientes

## 📊 Resultados do Modelo

| Métrica              | Valor     |
|----------------------|-----------|
| AUC-ROC (teste)      | ~0.72     |
| Acurácia (treino balanceado) | ~65-67% |
| Principais variáveis | age, cholesterol, imc, weight |

**Melhoria significativa** após incluir a feature IMC.

## 📁 Estrutura do Projeto
predicao-doencas-cardiovasculares/
├── Profissao Cientista de Dados M27 Pratique.ipynb
├── CARDIO_BASE.csv
├── README.md


## 🚀 Como executar
1. Clone o repositório
2. Instale as dependências:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn

Abra o notebook no Jupyter ou Google Colab

📌 Conclusão
O modelo demonstrou boa capacidade preditiva, com destaque para as variáveis idade, colesterol e IMC. Projeto ideal para portfólio de Ciência de Dados / Machine Learning.

Feito com ❤️ por Deeline Design
<img src="https://img.shields.io/badge/LinkedIn-Rodrigo%20Ribeiro-blue" alt="LinkedIn">

