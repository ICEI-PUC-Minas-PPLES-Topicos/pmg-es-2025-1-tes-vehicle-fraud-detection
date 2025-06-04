# Análise Preditiva Aplicada à Identificação de Fraudes em Seguros Automotivos

Repositório destinado ao desenvolvimento e publicação dos experimentos realizados para o estudo de detecção de fraudes em pedidos de seguros automotivos, utilizando técnicas de **Machine Learning**.

Este projeto foi desenvolvido como parte das atividades da disciplina de **Desenvolvimento de Aplicações Distribuídas**, do curso de Ciência da Computação da **PUC Minas**.

## Objetivo

O objetivo deste trabalho é avaliar a eficácia de diferentes modelos de aprendizado de máquina na identificação de fraudes em seguros automotivos, contribuindo para mitigar prejuízos financeiros e melhorar a eficiência operacional de seguradoras.

Foram utilizados os seguintes algoritmos de classificação binária:

* Regressão Logística
* Naïve Bayes
* Máquinas de Vetores de Suporte (SVM)
* Floresta de Decisão (Random Forest)

A avaliação considerou cenários com dados balanceados e desbalanceados (com aplicação do método **SMOTE**), utilizando métricas como **Acurácia, Precisão, Revocação e F1-Score**.

## Integrantes da Equipe

* Gabriel Estevão N. Sobrinho – [gensobrinho@gmail.com](mailto:gensobrinho@gmail.com)
* Letícia T. Lott – [lott.ltc@gmail.com](mailto:lott.ltc@gmail.com)
* Luana G. Fleury – [luana.fleury4@gmail.com](mailto:luana.fleury4@gmail.com)
* Rafael F. Barra – [rafafbarra@gmail.com](mailto:rafafbarra@gmail.com)
* Yan R. Nalon – [yanrnalon@gmail.com](mailto:yanrnalon@gmail.com)

## Professor Responsável

* Leonardo Vilela Cardoso 

## Tecnologias e Bibliotecas Utilizadas

* Python
* Pandas
* Scikit-learn
* Jupyter Notebook (para desenvolvimento e experimentação)

As bibliotecas externas utilzadas para extração de modelos e algoritmos estão contidas no diretório `códigos/libs/libs.zip`.

## Instruções de Uso

1. Clone este repositório
2. Em uma IDE apropriada, como VSCode, importe execute o Jupyter Notebook contido em `/códigos/automotive_fraud_detection.ipynb`
