# 📊 Modelo de Previsão de Cancelamento de Clientes

Este projeto tem como objetivo prever o **cancelamento de clientes** (churn) utilizando técnicas de Machine Learning aplicadas a um conjunto de dados históricos de uma empresa de telecomunicações.

---

## 🧠 Objetivo

Desenvolver um modelo preditivo capaz de identificar clientes com maior probabilidade de cancelarem seus serviços, permitindo que a empresa adote ações preventivas de retenção.

---

## 📁 Estrutura do Projeto

O projeto está estruturado em um Jupyter Notebook com as seguintes etapas:

### 1. **Importação das Bibliotecas**

As bibliotecas principais utilizadas são:

- `pandas` e `numpy`: manipulação e análise de dados
- `seaborn` e `matplotlib`: visualização gráfica
- `sklearn`: machine learning e avaliação de modelos

### 2. **Carregamento do Dataset**

Foi utilizado um dataset com informações demográficas, contratuais e comportamentais dos clientes, contendo a variável alvo `Churn` (Cancelamento).

### 3. **Análise Exploratória de Dados (EDA)**

- Verificação de dados nulos
- Distribuição das variáveis
- Análise da variável `Churn`
- Correlação entre atributos

### 4. **Pré-processamento**

- Conversão de variáveis categóricas com `get_dummies`
- Padronização de atributos numéricos com `StandardScaler`
- Separação entre features (X) e target (y)
- Divisão dos dados em treino e teste

### 5. **Treinamento dos Modelos**

Foram testados diversos algoritmos:

- **Logistic Regression**
- **Random Forest**
- **Decision Tree**
- **K-Nearest Neighbors (KNN)**
- **SVM (Support Vector Machine)**

### 6. **Avaliação de Desempenho**

Utilização de métricas como:

- Acurácia
- Matriz de confusão
- Precisão, Recall, F1-Score
- ROC AUC Score

### 7. **Comparação entre Modelos**

Após o treinamento, os modelos foram comparados com base em seu desempenho nas métricas listadas. O modelo com melhor performance foi escolhido como o final.

---

## 📌 Requisitos

- Python 3.7+
- Jupyter Notebook
- Pacotes Python:
  ```bash
  pip install pandas numpy matplotlib seaborn scikit-learn
  ```

---

## 🏁 Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```

2. Acesse o diretório:
   ```bash
   cd seu-repositorio
   ```

3. Execute o Jupyter Notebook:
   ```bash
   jupyter notebook ModeloPrevisaoCancelamento.ipynb
   ```

---

## 📊 Dataset

Caso o dataset seja público, inclua aqui:

- Nome: Ex: Telco Customer Churn Dataset
- Fonte: [Kaggle Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)

---

## 💡 Conclusão

O modelo construído permite prever com boa precisão quais clientes têm maior probabilidade de cancelamento, possibilitando a criação de campanhas direcionadas para retenção e redução do churn.

---

## 📈 Melhorias Futuras

- Testar novos algoritmos de ensemble
- Ajuste de hiperparâmetros com GridSearchCV
- Implementação em produção via API
- Análise de SHAP para interpretabilidade do modelo

---
