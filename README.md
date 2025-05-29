# 🐧 Projeto de Visualização de Dados e Classificação de Pinguins

Este projeto combina **análise exploratória de dados** e **modelos de machine learning** usando o famoso conjunto de dados dos pinguins de Palmer. O objetivo é compreender melhor as características dos pinguins resgatados por uma ONG e aplicar modelos de classificação para prever suas espécies com base em medidas corporais.

---

## 📊 Perguntas de Pesquisa

A visualização de dados na `main` do projeto busca responder as seguintes perguntas:

1. **Quais pinguins não têm anotações?**  
   (Dados ausentes ou incompletos por categoria)

2. **Quais ilhas a maioria dos pinguins está vindo?**  
   (Distribuição geográfica)

3. **Quais as espécies que a ONG mais possui?**  
   (Frequência por espécie)

4. **Existe alguma relação entre as medidas do pinguim e a sua espécie?**  
   (Visualizações comparativas de atributos como comprimento do bico, massa corporal etc.)

5. **Existe alguma relação entre as medidas do pinguim e seu sexo para cada uma das três espécies?**  
   (Análise multivariada entre medidas e sexo dentro de cada espécie)

---

## 🧠 Machine Learning

O projeto possui três branches adicionais, cada uma com a aplicação e análise de um modelo de classificação supervisionada:

- [`branch-knn`](https://github.com/XaNd204/ML/blob/branch-KNN):  
  Classificador **KNN (K-Nearest Neighbors)** com ajuste de `k` e validação cruzada.  
  Normalização é essencial para o bom desempenho.

- [`branch-svm`](https://github.com/XaNd204/ML/blob/branch-SVM):  
  **SVM linear** com divisão treino/teste e validação cruzada.

- [`branch-svm-kernel`](https://github.com/XaNd204/ML/blob/branch-SVMwKernelTrick):  
  **SVM com kernel não-linear (RBF)** e ajuste do parâmetro `gamma`, com resultados de alta acurácia.

---

## 🛠️ Tecnologias Utilizadas

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (SVM, KNN, validação cruzada)
- Jupyter Notebook

---

## 🚀 Como Executar

1. Clone o repositório:

```bash
git clone https://github.com/seuusuario/seurepositorio.git
cd ML
