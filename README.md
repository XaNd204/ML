#  Análise e Classificação de Espécies de Pinguins de Palmer

Este projeto realiza uma análise exploratória de dados e implementa modelos de Machine Learning para classificar espécies de pinguins com base em suas medidas corporais. O trabalho utiliza o famoso conjunto de dados **Palmer Penguins**.

O objetivo é duplo:
1.  **Análise Exploratória:** Entender as características das diferentes espécies de pinguins, suas distribuições geográficas e as relações entre suas medidas.
2.  **Modelagem Preditiva:** Construir e avaliar três modelos de classificação supervisionada (KNN, SVM Linear e SVM com Kernel RBF) para prever a espécie de um pinguim.

![Exemplo de Pairplot mostrando a relação entre as medidas](images\pairplot_hue=espece.png")

##  Perguntas de Pesquisa

A análise exploratória foi guiada pelas seguintes questões:

1.  **Dados Ausentes:** Quais são as características com dados faltantes e em que quantidade?
2.  **Distribuição Geográfica:** Qual a distribuição das espécies de pinguins por ilha?
3.  **Frequência das Espécies:** Qual a espécie mais comum no conjunto de dados?
4.  **Medidas vs. Espécie:** Existe uma correlação visível entre as medidas corporais (comprimento e profundidade do bico, comprimento da nadadeira, massa) e a espécie do pinguim?
5.  **Medidas vs. Sexo:** Como as medidas corporais variam entre machos e fêmeas dentro de cada espécie?

##  Modelos de Machine Learning

O projeto explora três algoritmos de classificação. Cada modelo está implementado em uma `branch` separada para melhor organização. A análise exploratória principal se encontra na branch `main`.

* `branch-KNN`: Implementação do classificador **K-Nearest Neighbors (KNN)**. Inclui ajuste de hiperparâmetros (`k`) com validação cruzada. A normalização dos dados foi um passo crucial para a performance deste modelo.
* `branch-SVM`: Implementação de um **Support Vector Machine (SVM) com kernel linear**.
* `branch-SVMwKernelTrick`: Implementação de um **SVM com kernel não-linear (RBF)**, que se mostrou o modelo de melhor performance, com excelente capacidade de generalização.

###  Resultados Comparativos

A tabela abaixo resume a performance dos modelos no conjunto de teste:

| Modelo             | Acurácia | Precisão (Média Ponderada) |
| :----------------- | :------: | :------------------------: |
| KNN (k=5)          |   0.96   |            0.96            |
| SVM Linear         |   0.98   |            0.98            |
| **SVM (Kernel RBF)** | **0.99** |          **0.99** |


##  Tecnologias Utilizadas

* **Linguagem:** Python 3.9+
* **Bibliotecas Principais:**
    * `pandas`
    * `numpy`
    * `matplotlib`
    * `seaborn`
    * `scikit-learn`

##  Como Executar

**1. Clone o Repositório**
```bash
git clone [https://github.com/XaNd204/ML.git](https://github.com/XaNd204/ML.git)
cd ML
