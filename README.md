# Heart Attack Detection

## Overview
Este repositório contém um experimento de detecção de ataques cardíacos realizado no Microsoft Machine Learning Studio. O projeto visa criar um modelo de aprendizado de máquina capaz de prever a ocorrência de ataques cardíacos com base em conjuntos de dados específicos.

## Estrutura do Repositório
- **Data:** Esta pasta contém os conjuntos de dados utilizados no projeto.
- **Model:** Aqui você encontrará o arquivo `data_analysis.ipynb`, que agora inclui tanto a análise exploratória do dataset quanto o processo de modelagem, testes e ajuste fino dos parâmetros do modelo.

## Agradecimentos
Gostaríamos de expressar nossa gratidão aos seguintes recursos que foram fundamentais para o desenvolvimento deste projeto:

- **Dataset:** O dataset utilizado neste projeto foi obtido a partir do Kaggle e pode ser encontrado [aqui](https://www.kaggle.com/datasets/rashikrahmanpritom/heart-attack-analysis-prediction-dataset). Agradecemos ao autor pela disponibilização desses dados valiosos.

- **Análise Exploratória de Dados (EDA):** Utilizamos como referência e inspiração um notebook do Kaggle disponível [aqui](https://www.kaggle.com/code/namanmanchanda/heart-attack-eda-prediction-90-accuracy) para a análise exploratória de dados, que influenciou as escolhas durante a fase de modelagem.

## Sumário do Notebook
O notebook `data_analysis.ipynb` está estruturado da seguinte forma:

# Sumário

[Introdução](#1) <a id=180></a>
1. [Importação, Transformação e Limpeza de Dados](#2)
    - 1.1 [Configurações Gerais](#3)
    - 1.2 [Importar Dataframe](#4)
    - 1.3 [Entendendo os dados](#5)
2. [Análise Exploratória de Dados (EDA)](#6)
    - 2.1 [Análise Univariada](#7)
    - 2.2 [Análise Bivariada](#8)
3. [Pré-processamento de Dados](#11)
    - 3.1 [Conclusões da EDA](#12)
    - 3.2 [Instalando pacotes](#13)
    - 3.3 [Configurando Caracteristicas para o modelo](#14)
4. [Modelagem](#15)
    - 4.1 [Classificadores Lineares](#16)
    - 4.2 [Modelos de Árvore](#17)
    - 4.3 [Acurácia dos Modelos](#18)
5. [Implantação no Machine Learning Studio](19)
    - 5.1 [Modelagem do Pipeline](20)
    - 5.2 [Web Services](21)
6. [Conclusão](23)

