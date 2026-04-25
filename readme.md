# 🍷 Predição de Qualidade de Vinhos com Redes Neurais

![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=flat&logo=PyTorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=flat&logo=scikit-learn&logoColor=white)
![Status](https://img.shields.io/badge/Status-Concluído-success)

Este repositório contém a solução para o trabalho prático de **Aprendizado Supervisionado com Redes Neurais Artificiais**, desenvolvido para a disciplina de Inteligência Artificial da Universidade do Distrito Federal (UnDF).

O objetivo do projeto é classificar amostras de vinho tinto português (Vinho Verde) em duas categorias ("Bom" ou "Regular") com base em 11 propriedades físico-químicas, lidando com um cenário real de **dados desbalanceados**.

**Autor:** Bianco Da Costa Oliveira  
**Professor:** Marcio Andrey Roselli  
**Dataset:** [Wine Quality (Cortez et al., 2009)](https://archive.ics.uci.edu/ml/datasets/wine+quality)

---

## 📂 Estrutura do Repositório

O projeto segue as melhores práticas de Engenharia de Dados e Machine Learning, separando o pré-processamento da modelagem.

```text
wine-quality-nn/
├── data/
│   ├── raw/                 # Dados brutos baixados diretamente do UCI
│   └── processed/           # Dados normalizados e balanceados (SMOTE)
├── notebooks/
│   ├── 01-eda.ipynb         # Análise Exploratória de Dados (EDA)
│   ├── 02-preprocessing.ipynb # Divisão, Normalização e SMOTE
│   └── 03-modeling.ipynb    # Treinamento do Baseline e da Rede Neural
├── src/
│   └── main.ipynb           # Notebook final com todas as etapas de uma vez
├── requirements.txt         # Dependências do projeto
└── README.md
```
