# Módulo 3: Classificação

## Visão geral do módulo

### Contexto
Este módulo apresenta os **principais algoritmos de classificação** utilizados na prática. Aqui você aprenderá como resolver problemas onde o objetivo é prever categorias discretas (sim/não, spam/legítimo, iris-setosa/versicolor/virginica, etc.). Cada algoritmo tem seus próprios pontos fortes, fraquezas e premissas matemáticas. Este módulo o equipará com uma "caixa de ferramentas" de classificadores, desde os mais simples (KNN baseado em distância) até os mais sofisticados (ensembles). Você compreenderá **quando e por que usar cada um**.

### Estrutura
Este módulo contém **6 notebooks**:

1. **01_knn.ipynb** — K-Nearest Neighbors (KNN)
   - Algoritmo baseado em instâncias
   - Classificação por votação dos vizinhos mais próximos
   - Impacto do hiperparâmetro K
   - Normalização essencial

2. **02_naive_bayes.ipynb** — Naive Bayes
   - Classificação probabilística baseada em Teorema de Bayes
   - Hipótese de independência condicional
   - Variantes: Gaussian, Multinomial, Bernoulli
   - Aplicações em classificação de texto (detecção de spam)

3. **03_regressao_logistica.ipynb** — Regressão Logística
   - Função sigmoide e log-odds
   - Gradiente descendente para otimização
   - Interpretação de probabilidades e coeficientes
   - Aplicação no dataset Titanic

4. **04_svm.ipynb** — Support Vector Machines (SVM)
   - Maximização de margem de separação
   - Kernel trick para dados não-lineares
   - Regularização via C
   - Classificação binária e one-vs-rest para multiclasse

5. **05_arvores_classificacao.ipynb** — Árvores de Decisão
   - Construção de árvores por particionamento recursivo
   - Critérios de impureza (Gini, Entropia)
   - Controle de profundidade (prevenção de overfitting)
   - Interpretabilidade visual das decisões

6. **06_ensemble_classificacao.ipynb** — Métodos Ensemble
   - Random Forest (ensemble de árvores)
   - Gradient Boosting
   - Votação e empilhamento (Stacking)
   - Redução de variância via ensemble

### Tempo Estimado
- **Notebook 1 (KNN):** 45-60 minutos (intuição + implementação)
- **Notebook 2 (Naive Bayes):** 45-60 minutos (probabilidade + texto)
- **Notebook 3 (Regressão Logística):** 50-70 minutos (matemática + Titanic)
- **Notebook 4 (SVM):** 50-70 minutos (otimização + kernels)
- **Notebook 5 (Árvores):** 45-60 minutos (recursão + visualização)
- **Notebook 6 (Ensemble):** 50-70 minutos (combinação de modelos)
- **Total do Módulo:** 4h45min - 6h30min

---

## Fontes (bibliografia principal)
- Müller, A. C., & Guido, S. (2016). Introduction to machine learning with python: A guide for data scientists. O'Reilly Media, Inc. 

- Géron, A. (2022). Hands-on machine learning with Scikit-Learn, Keras, and TensorFlow: Concepts, tools, and techniques to build intelligent systems (3rd ed.). O'Reilly Media.

- [Logistic Regression in Machine Learning](https://www.geeksforgeeks.org/machine-learning/understanding-logistic-regression/). GeeksForGeeks.
- [Kernel Trick in Support Vector Classification](https://www.geeksforgeeks.org/machine-learning/kernel-trick-in-support-vector-classification/). GeeksForGeeks.
- [What Is a Support Vector Machine?](https://uk.mathworks.com/discovery/support-vector-machine.html). MathWorks
- [O que são máquinas de vetores de suporte (SVMs)?](https://www.ibm.com/br-pt/think/topics/support-vector-machine). IBM.





---

## Saber mais (leituras complementares)
- **destaques:**
   - **Regularização:** [Logistic Regression and Regularization](https://medium.com/@rithpansanga/logistic-regression-and-regularization-avoiding-overfitting-and-improving-generalization-e9afdcddd09d)
   - **Softmax Regression:** [Multinomial Logistic Regression](https://rasbt.github.io/mlxtend/user_guide/classifier/SoftmaxRegression/)
   - **Fundamentos:** [Understanding Logistic Regression](https://www.geeksforgeeks.org/machine-learning/understanding-logistic-regression/)


- **Documentação Oficial:**
   - [Scikit-Learn: SVM](https://scikit-learn.org/stable/modules/svm.html)
   - [SVC API Reference](https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html)
   - [SVR API Reference](https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVR.html)
   - [VotingClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.VotingClassifier.html)
   - [XGBoost](https://xgboost.readthedocs.io/en/stable/)
   - [LightGBM](https://lightgbm.readthedocs.io/en/stable/Python-Intro.html)
   - [CatBoost](https://catboost.ai/docs/en/concepts/python-installation)

- **Tutoriais e Artigos:**
   - Drew Wilimitis. [The Kernel Trick](https://medium.com/data-science/the-kernel-trick-c98cdbcaeb3f). Medium
   - Nara Guimaraes. [Regressão Logística: Como usá-la em análise de dados](https://medium.com/@nara.guimaraes/regress%C3%A3o-log%C3%ADstica-como-usu%C3%A1-la-em-an%C3%A1lise-de-dados-3fdb6be3a255). Medium.
   - Bernardo Coutinho. [Modelos de Predição](https://medium.com/turing-talks/turing-talks-12-classifica%C3%A7%C3%A3o-por-svm-f4598094a3f1). Medium.
   - Samy Baladram. [Decision Tree Classifier, Explained: A Visual Guide with Code Examples for Beginners](https://medium.com/data-science/decision-tree-classifier-explained-a-visual-guide-with-code-examples-for-beginners-7c863f06a71e). Medium.
   - Sunil Ray. [Understanding Support Vector Machine](https://www.analyticsvidhya.com/blog/2017/09/understaing-support-vector-machine-example-code/). Analytics Vidhya.
   - Avinash Navlani. [SVM Tutorial](https://www.datacamp.com/tutorial/svm-classification-scikit-learn-python). DataCamp
   - Avinash Naviani. [Tutorial sobre classificação por árvore de decisão em Python](https://www.datacamp.com/pt/tutorial/decision-tree-classification-python). DataCamp
   - Gabriel Sacramento. [Árvore de decisão: entenda esse algoritmo de Machine Learning](https://blog.somostera.com/data-science/arvores-de-decisao). Blog Somostera.

- **Vídeos Recomendados:**
   - [StatQuest: Support Vector Machines](https://www.youtube.com/watch?v=efR1C6CvhmE)
   - [SVM with Polynomial Kernel Visualization](https://www.youtube.com/watch?v=3liCbRZPrZA)
   - [Pedram Jahangiry](https://www.youtube.com/@pedramjahangiry)

---

## Palavras-chave do módulo
- K-Nearest Neighbors (KNN)
- Distância Euclidiana
- Naive Bayes
- Teorema de Bayes
- Regressão Logística
- Função Sigmoide
- Gradiente Descendente
- Support Vector Machines (SVM)
- Kernel Trick
- Árvore de Decisão
- Entropia
- Ganho de Informação
- Random Forest
- Gradient Boosting
- Método Ensemble

---

## Autores

- Felipe Melo
- Henrique Nogueira Pedro Lindoso
- Igor Pires Ferreira
- Maisa Lumi Sonoda

---
