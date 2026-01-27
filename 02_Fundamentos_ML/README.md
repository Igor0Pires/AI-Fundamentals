# Módulo 2: Fundamentos de Machine Learning

## Visão geral do módulo

### Contexto
Este módulo é a ponte entre os conceitos fundamentais (Módulo 1) e a implementação de algoritmos específicos (Módulos 3 e 4). Aqui você aprenderá os **princípios universais** que governam todos os modelos de machine learning: como classificar diferentes tipos de modelos, entender o trade-off entre bias e variância, e validar modelos de forma rigorosa. Esses conceitos são **críticos para construir modelos que generalizem bem** e não "decorar" padrões dos dados de treinamento.

### Estrutura
Este módulo contém **4 notebooks**:

1. **01_modelos_validacao.ipynb** — Modelos e Validação
   - Categorias de modelos preditivos (estatísticos, otimização, particionamento, clustering, baseados em instâncias)
   - Trade-off Bias-Variância (Underfitting vs Overfitting)
   - Validação cruzada (K-Fold para dados i.i.d. e Rolling Window para séries temporais)

2. **02_metricas_classificacao.ipynb** — Métricas de Classificação
   - Tipos de classificação (binária, multiclasse, multirótulo, desbalanceada)
   - O que é um classificador
   - Introdução ao dataset Wine (análise química de vinhos)

3. **03_metricas_regressao.ipynb** — Métricas de Regressão
   - Problemas de regressão (previsão de valores contínuos)
   - Métricas específicas (MSE, RMSE, MAE, R²)
   - Interpretação de erros em contextos práticos

4. **04_feature_engineering.ipynb** — Engenharia de Features
   - Criação e transformação de features
   - Seleção de features relevantes
   - Tratamento de dados faltantes e outliers
   - Normalização e padronização

### Tempo Estimado
- **Notebook 1:** 40-50 minutos (matemática densa + conceitos)
- **Notebook 2:** 30-40 minutos (conceitual com exemplos)
- **Notebook 3:** 30-40 minutos (métricas de regressão)
- **Notebook 4:** 45-60 minutos (técnicas práticas com código)
- **Total do Módulo:** 2h45min - 3h30min

---

## Fontes (bibliografia principal)

- Lee, F. [What is bias-variance tradeoff?](https://www.ibm.com/think/topics/bias-variance-tradeoff). IBM
- Carlos Alberto Bonfim. [O que é bias-variance tradeoff](https://medium.com/data-hackers/o-que-é-bias-variance-tradeoff-a5bc19866e4b). Medium
- João Vitor Savietto. [Machine Learning: Métricas, Validação Cruzada, Bias e Variância](https://medium.com/@jvsavietto6/machine-learning-m%C3%A9tricas-valida%C3%A7%C3%A3o-cruzada-bias-e-vari%C3%A2ncia-380513d97c95). Medium
- Jacob Murel Ph.D. e Eda Kavlakoglu.[classification-models](https://www.ibm.com/br-pt/think/topics/classification-models). IBM
- Clébio Júnior. [Indo Além da Acurácia: Entendo a Acurácia Balanceada, Precisão, Recall e F1 score](https://medium.com/data-hackers/indo-al%C3%A9m-da-acur%C3%A1cia-entendo-a-acur%C3%A1cia-balanceada-precis%C3%A3o-recall-e-f1-score-c895e55a9753). Medium
- Gustavo Candido. [Curva ROC e AUC](https://medium.com/@lg0702/curva-roc-e-au-2ecb57267149). Medium
- Edson Junior. [Principais métricas de avaliação de modelos em Machine Learning](https://medium.com/data-hackers/principais-métricas-de-classificação-de-modelos-em-machine-learning-94eeb4b40ea9). Medium
- João Cláudio Nunes Carvalho. [O algoritmo Naive Bayes — descrição e implementação em Python](https://joaoclaudionc.medium.com/o-algoritmo-naive-bayes-descrição-e-implementação-em-python-35757ade6b36). Medium
- Felipe Azank. [Como avaliar seu modelo de regressão](https://medium.com/turing-talks/como-avaliar-seu-modelo-de-regress%C3%A3o-c2c8d73dab96). Medium
- Kauã Fillipe. [Introdução à Feature Engineering para Previsão com Séries Temporais](https://medium.com/turing-talks/introdu%C3%A7%C3%A3o-%C3%A0-feature-engineering-para-previs%C3%A3o-com-s%C3%A9ries-temporais-bf8bd3d0397d). Medium
- Vanessa Leiko. [One-hot encoding, input features, overfitting: conhece esses termos de Machine Learning?](https://medium.com/@vanleiko/one-hot-encoding-input-features-overfitting-conhece-esses-termos-de-machine-learning-328d22ae1c25). Medium
- Iury Rosal. [Engenharia de Features: Transformando dados categóricos em dados numéricos](https://medium.com/data-hackers/engenharia-de-features-transformando-dados-categóricos-em-dados-numéricos-e5d3991df715). Medium
- Nadinne Cavalcante. [Manipulando os Outliers](https://medium.com/@nadinne.cavalcante94/manipulando-os-outliers-eb0a8bfdf5fe). Medium

---

## Saber mais (leituras complementares)

[Documentação Scikit-Learn](https://scikit-learn.org/stable/)

---

## Palavras-chave do módulo
- Modelo Preditivo
- Bias (Viés)
- Variância
- Underfitting (Subajuste)
- Overfitting (Superajuste)
- Validação Cruzada (K-Fold CV)
- Classificação Binária
- Classificação Multiclasse
- Dados Desbalanceados
- Acurácia
- Precision
- Recall
- F1-Score
- MSE (Mean Squared Error)
- R² (Coeficiente de Determinação)
- Feature Engineering
- Normalização
- Outliers

---

## Autor

- Maisa Lumi Sonoda
- Thales Vieira Rodrigues

---
