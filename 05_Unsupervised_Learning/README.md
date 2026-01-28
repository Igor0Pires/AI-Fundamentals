# Módulo 5: Aprendizado Não-Supervisionado

## Visão geral do módulo

### Contexto
Neste módulo exploramos como aprender a estrutura dos dados **sem rótulos**. Em vez de prever respostas conhecidas, buscamos padrões, agrupamentos e representações compactas. Você verá como redução de dimensionalidade ajuda a revelar e comprimir informação essencial, e como diferentes algoritmos de clustering identificam grupos naturais, detectam anomalias e geram novas features para modelos supervisionados dos módulos anteriores.

### Estrutura
Este módulo contém **3 notebooks**:

1. **01_introducao.ipynb** — Introdução ao Unsupervised Learning
	- Intuição exploratória e papel de UL na geração de hipóteses
	- Como UL apoia análise visual, detecção de outliers e criação de novas features
	- Conexão com módulos anteriores (engenharia de features, preparação de dados)

2. **02_dimensionality_reduction.ipynb** — Redução de Dimensionalidade (PCA e LLE)
	- Maldição da dimensionalidade e diferenças entre projeção linear e manifold learning
	- PCA: intuição, formulação matemática, variância explicada, scree plot e impacto em classificadores
	- LLE: preservação de vizinhança, comparação com PCA, visualização com Swiss Roll
	- Panorama de outros métodos (t-SNE, Isomap, Kernel PCA, Autoencoders)

3. **03_clustering.ipynb** — Clustering (K-Means, DBSCAN, GMM)
	- K-Means: intuição geométrica, formulação, escolha de k (elbow, silhueta), análise de clusters
	- DBSCAN: noção de densidade, escolha de eps/min_samples, robustez a formatos variados
	- Gaussian Mixture Models: abordagem probabilística, BIC/AIC para número de componentes, incerteza
	- Comparações práticas e menção a extensões como HDBSCAN

### Tempo Estimado
- **Notebook 1 (Introdução):** 20-30 minutos (conceitos e aplicações)
- **Notebook 2 (Redução de Dimensionalidade):** 60-80 minutos (intuição, matemática, prática)
- **Notebook 3 (Clustering):** 70-90 minutos (múltiplos algoritmos e comparações)
- **Total do Módulo:** 2h30min - 3h20min

---

## Fontes (bibliografia principal)

- Géron, A. (2022). Hands-on machine learning with Scikit-Learn, Keras, and TensorFlow: Concepts, tools, and techniques to build intelligent systems (3rd ed.). O'Reilly Media.

- Seltman, Howard J. (2018). [Exploratory Data Analysis](https://www.stat.cmu.edu/~hseltman/309/Book/chapter4.pdf). Carnegie Mellon University 

- Prof. Marcelo de Souza Lauretto. (2011). [Análise Exploratória de Dados](https://www.each.usp.br/lauretto/SIN5008_2011/aula01/aula1). EACH-USP 
- [DBSCAN Clustering in ML - Density based clustering](https://www.geeksforgeeks.org/machine-learning/dbscan-clustering-in-ml-density-based-clustering/). GeeksForGeeks.
- [Gaussian Mixture Model](https://www.geeksforgeeks.org/machine-learning/gaussian-mixture-model/). GeeksForGeeks.
- [K means Clustering](https://www.geeksforgeeks.org/machine-learning/k-means-clustering-introduction/). GeeksForGeeks.
- [What ls Unsupervised Learning?](https://www.mathworks.com/discovery/unsupervised-learning.html). MathWorks 
- Kurtis Pykes. [Introdução ao aprendizado não supervisionado](https://www.datacamp.com/pt/blog/introduction-to-unsupervised-learning). DataCamp
- Analytics Vidhya. [Classification vs. Clustering- Which One is Right for Your Data?](https://www.analyticsvidhya.com/blog/2023/05/classification-vs-clustering/). Analytics Vidhya 
---

## Saber mais (leituras complementares)
- **destaques:**
	- [Machine Learning](https://www.geeksforgeeks.org/machine-learning/machine-learning/). GeeksForGeeks.

- **Tutoriais e Artigos:**
	- Mark Taylor. [Supervised vs. Unsupervised Learning: Understanding the Key Differences](https://taylor-mark110.medium.com/supervised-vs-unsupervised-learning-understanding-the-key-differences-d43a3c8ede82). Medium
	- Gouranga Jha. [A Holistic Guide to Exploratory Data Analysis (EDA) for Machine Learning and Deep Learning](https://medium.com/@post.gourang/a-holistic-guide-to-exploratory-data-analysis-eda-for-machine-learning-and-deep-learning-bc4f18f0143b). Medium
- **vídeos recomendados:**
	- Christine Jiang. [Portfolio Playbook](https://youtube.com/playlist?list=PLA_6vBVye4w2UjCNBeAlDj1UFVxcYkRng&si=5wER6GZhwR8xqPbW). Youtube.
	- [DeepMind x UCL | Deep Learning Lecture Series 2021](https://youtube.com/playlist?list=PLqYmG7hTraZDVH599EItlEWsUOsJbAodm&si=p2qpO23xwGCceFSO)	
	- [MIT 15.773 Hands-On Deep Learning Spring 2024](https://youtube.com/playlist?list=PLUl4u3cNGP60YyhMjYmXuVmX562QcClSp&si=YwR8k4PGpK6R1Fbt)

- **Documentação oficial:**
	- [`sklearn.manifold.TSNE`](https://scikit-learn.org/stable/modules/generated/sklearn.manifold.TSNE.html)
	- [`sklearn.manifold.Isomap`](https://scikit-learn.org/stable/modules/generated/sklearn.manifold.Isomap.html)
	- [`sklearn.decomposition.KernelPCA`](https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.KernelPCA.html)
	- [`sklearn.cluster.AgglomerativeClustering`](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.AgglomerativeClustering.html)
	- [`sklearn.cluster.SpectralClustering`](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.SpectralClustering.html)
	- [`sklearn.cluster.AffinityPropagation`](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.AffinityPropagation.html)
	- [`sklearn.cluster.MeanShift`](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.MeanShift.html)
	- [`sklearn.cluster.HDBSCAN`](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.HDBSCAN.html)


---

## Palavras-chave do módulo
- Unsupervised Learning
- Redução de Dimensionalidade
- PCA, Variância Explicada, Scree Plot
- LLE, Manifold Learning
- t-SNE, Isomap, Kernel PCA, Autoencoders
- Clustering, K-Means, DBSCAN, Gaussian Mixture Models (GMM)
- Elbow Method, Silhouette, Davies-Bouldin
- Detecção de Anomalias
- Engenharia de Features com Clusters/Componentes

---

## Autores

- Igor Pires Ferreira
- Lucas Antonio Pataluch dos Santos

---
