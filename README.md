# 🚗 Análise e Previsão de Preços de Carros Usados

> **Projeto de Ciência de Dados e Machine Learning aplicado à análise do mercado de veículos usados e à previsão de preços.**

Este repositório apresenta um projeto desenvolvido durante os estudos de **Programação para Ciência dos Dados**, utilizando técnicas de análise exploratória, preparação de dados, engenharia de atributos e **Aprendizado de Máquina**.

O objetivo é analisar características de veículos usados e desenvolver modelos capazes de **estimar seus preços**, utilizando dados históricos como base para as previsões.

---

## 🎯 Objetivo

Desenvolver uma solução baseada em dados para compreender os principais fatores relacionados ao preço de veículos usados e aplicar modelos de Machine Learning para realizar previsões.

O projeto percorre diferentes etapas de um fluxo de Ciência de Dados:

```text id="9slk6x"
Dados
  ↓
Inspeção
  ↓
Limpeza e tratamento
  ↓
Análise exploratória
  ↓
Engenharia de atributos
  ↓
Preparação das variáveis
  ↓
Treinamento dos modelos
  ↓
Avaliação
  ↓
Previsão de preços
```

---

## 🔎 Sobre o projeto

A análise utiliza informações sobre veículos usados para investigar características que podem influenciar seus valores de mercado.

Entre as etapas desenvolvidas estão:

* inspeção inicial dos dados;
* análise das características dos veículos;
* tratamento de valores ausentes;
* identificação e tratamento de outliers;
* transformação de variáveis;
* engenharia de atributos;
* seleção de características;
* visualização dos dados;
* treinamento de modelos;
* avaliação do desempenho;
* previsão de preços.

---

## 📊 Análise Exploratória

A análise exploratória busca identificar padrões e relações entre as características dos veículos e seus respectivos preços.

São utilizadas técnicas de visualização e estatística para compreender:

* distribuição dos preços;
* características dos veículos;
* relação entre variáveis;
* comportamento dos dados;
* possíveis valores discrepantes;
* fatores que podem influenciar o preço.

---

## 🧹 Pré-processamento

Antes do treinamento dos modelos, os dados passam por etapas de preparação.

### Tratamento de valores ausentes

Foi utilizada **imputação por KNN (K-Nearest Neighbors)** para tratar valores ausentes, utilizando a relação entre as observações para estimar valores.

### Tratamento de outliers

São analisados valores potencialmente discrepantes que podem influenciar negativamente o treinamento dos modelos.

### Transformação de variáveis

Variáveis categóricas e numéricas são preparadas para que possam ser utilizadas pelos algoritmos de Machine Learning.

---

## 🤖 Machine Learning

O projeto utiliza técnicas de **Aprendizado de Máquina supervisionado** para desenvolver modelos de previsão.

As etapas incluem:

* definição da variável-alvo;
* seleção das variáveis preditoras;
* divisão dos dados;
* treinamento;
* geração de previsões;
* avaliação dos modelos.

O problema é tratado como uma tarefa de **regressão**, uma vez que o objetivo é prever um valor numérico correspondente ao preço do veículo.

---

## 📈 Avaliação dos modelos

Os modelos são avaliados utilizando métricas apropriadas para problemas de regressão.

Entre as métricas utilizadas no projeto estão:

* **MAE — Mean Absolute Error**
* **MSE — Mean Squared Error**
* **RMSE — Root Mean Squared Error**
* **R² — Coeficiente de Determinação**

Essas métricas permitem comparar os modelos e identificar a abordagem com melhor desempenho para a previsão de preços.

---

## 🗂️ Arquivos do projeto

```text id="t0p9bj"
programacao_para_ciencia_dos_dados/
│
├── Aula_02_python_ciencia_de_dados.ipynb
│
├── ProjetoFinal_ML2.ipynb
│
├── trem.csv
│
├── test.csv
│
├── submission.csv
│
├── sample_submission.csv
│
├── LICENÇA
│
└── README.md
```

### 📓 Notebooks

**`Aula_02_python_ciencia_de_dados.ipynb`**
Material relacionado aos fundamentos de Python aplicados à Ciência de Dados.

**`ProjetoFinal_ML2.ipynb`**
Notebook principal do projeto, contendo as etapas de análise, preparação dos dados e Machine Learning.

### 📊 Dados

**`trem.csv`**
Conjunto de dados utilizado para treinamento.

**`test.csv`**
Conjunto de dados utilizado para teste.

### 📤 Resultados

**`submission.csv`**
Arquivo contendo as previsões geradas pelo modelo.

**`sample_submission.csv`**
Modelo de referência para o formato esperado da submissão.

---

## 🛠️ Tecnologias e bibliotecas

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge\&logo=pandas\&logoColor=white)
![Scikit Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge\&logo=scikit-learn\&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge\&logo=jupyter\&logoColor=white)

### Principais ferramentas

* **Python 3**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**
* **Category Encoders**
* **Jupyter Notebook / Google Colab**

---

## 🧠 Competências desenvolvidas

Este projeto demonstra conhecimentos práticos em:

`Python` · `Pandas` · `NumPy` · `EDA` · `Data Cleaning` · `Feature Engineering` · `KNN Imputation` · `Outlier Detection` · `Data Visualization` · `Machine Learning` · `Regression` · `Model Evaluation`

---

## 👥 Colaboradores

* **Matheus Nery de Souza Ferreira**
* **Pedras da Costa Machado Júnior**
* **Joelma Benício de Lima Printes**
* **Felipe Barros do Nascimento**
* **Luciano Carvalho da Rocha Filho**

---

## 🎓 Contexto acadêmico

Projeto desenvolvido no contexto acadêmico da disciplina **Programação para Ciência dos Dados**, aplicando conceitos de programação, análise de dados e Machine Learning a um problema relacionado ao mercado de veículos usados.

---

## 💡 Aplicação prática

Uma solução desse tipo pode auxiliar na análise do mercado de veículos usados, permitindo:

* compreender fatores relacionados ao preço;
* comparar características de diferentes veículos;
* identificar padrões nos dados;
* estimar preços com base em características observadas;
* apoiar análises orientadas por dados.

> **Observação:** as previsões produzidas pelo modelo possuem finalidade acadêmica e experimental e não devem ser utilizadas isoladamente como referência para decisões comerciais.

---

## 👩‍💻 Sobre a autora

### Joelma Printes

**Ciência de Dados | Machine Learning | Python | Análise de Dados**

📍 Manaus – AM – Brasil

🔗 [GitHub — joelma78](https://github.com/joelma78)

---

⭐ **Se este projeto foi útil ou interessante, considere deixar uma estrela no repositório.**

