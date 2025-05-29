#  Projeto de Visualização de Dados e Classificação de Pinguins

Este projeto combina **análise exploratória de dados** e **modelos de machine learning** utilizando o conjunto de dados dos pinguins de Palmer. O objetivo é compreender melhor as características dos pinguins resgatados por uma ONG e aplicar modelos de classificação para prever suas espécies com base em medidas corporais.

---

##  Perguntas de Pesquisa

A análise exploratória de dados busca responder às seguintes perguntas:

1. **Quais pinguins não têm anotações?**  
   (Identificação de dados ausentes ou incompletos por categoria)

2. **De quais ilhas a maioria dos pinguins está vindo?**  
   (Distribuição geográfica dos pinguins)

3. **Quais as espécies que a ONG mais possui?**  
   (Frequência por espécie)

4. **Existe alguma relação entre as medidas do pinguim e a sua espécie?**  
   (Análise comparativa de atributos como comprimento do bico, massa corporal, etc.)

5. **Existe alguma relação entre as medidas do pinguim e seu sexo para cada uma das três espécies?**  
   (Análise multivariada entre medidas e sexo dentro de cada espécie)

---

##  Modelos de Machine Learning

O projeto possui três branches adicionais, cada uma implementando um modelo de classificação supervisionada:

- [`branch-KNN`](https://github.com/XaNd204/ML/tree/branch-KNN):  
  Classificador **KNN (K-Nearest Neighbors)** com ajuste de `k` e validação cruzada.  
  > ⚠️ *Nota: A normalização dos dados é essencial para o bom desempenho deste modelo.*

- [`branch-SVM`](https://github.com/XaNd204/ML/tree/branch-SVM):  
  **SVM linear**, com divisão treino/teste e validação cruzada.

- [`branch-SVMwKernelTrick`](https://github.com/XaNd204/ML/tree/branch-SVMwKernelTrick):  
  **SVM com kernel não-linear (RBF)** e ajuste do parâmetro `gamma`.  
  Resultados com alta acurácia e excelente generalização.

---

##  Tecnologias Utilizadas

- **Linguagem:** Python 3.x
- **Bibliotecas:**
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn

---

##  Como Executar

1. Clone o repositório:

```bash
git clone https://github.com/XaNd204/ML.git
cd ML
