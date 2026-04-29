[![banner](/_assets/pics/bannerAI.jpg)](https://github.com/marcoteran/ml)

# SI7009 · Aprendizaje Automático
### Maestría en Ciencia de Datos y Analítica · Universidad EAFIT · 2026-1

<p align="left">
  <img src="https://img.shields.io/badge/curso-SI7009-0F2747?style=for-the-badge" alt="SI7009">
  <img src="https://img.shields.io/badge/programa-Maestría%20en%20Ciencia%20de%20Datos-173B63?style=for-the-badge" alt="Maestría">
  <img src="https://img.shields.io/badge/modalidad-Intensivo-1F2937?style=for-the-badge" alt="Intensivo">
  <img src="https://img.shields.io/badge/semestre-2026--1-6B7280?style=for-the-badge" alt="2026-1">
</p>

Repositorio oficial del curso **Aprendizaje Automático**.  
Aquí se publicarán las **diapositivas**, **notebooks**, **lineamientos de evaluación**, **taller**, **recursos complementarios** y materiales de apoyo del curso.

---

## Acceso rápido

- [Slides del curso](#slides-y-notebooks)
- [Evaluación](#evaluación)
- [Exposiciones](#exposiciones)
- [Tools](#tools)
- [Recursos recomendados](#recursos-recomendados)
- [Estructura del repositorio](#estructura-del-repositorio)

**Profesor:** [Marco Teran](https://marcoteran.github.io/)

---

## Sobre el curso

Curso intensivo y aplicado de nivel maestría enfocado en decisiones reales de **Machine Learning**:

- evaluación honesta y selección de métricas;
- clasificación desbalanceada;
- boosting moderno y ajuste de hiperparámetros;
- series de tiempo y validación temporal;
- recommendation systems;
- clustering, segmentación y confiabilidad del modelo.

La meta no es cubrir una enciclopedia de algoritmos, sino desarrollar **criterio técnico** para formular, validar, comparar e interpretar modelos de forma reproducible.

---

## Ruta del curso

| Sesión | Fecha | Tema central | Dataset / problema guía |
|---|---:|---|---|
| 1 | 2026-04-24 | Bienvenida + syllabus + evaluación moderna, desbalance y ensembles | Credit Card Fraud Detection |
| 2 | 2026-04-25 | Boosting moderno y optimización de hiperparámetros | Credit Card Fraud Detection |
| 3 | 2026-05-02 | Series de tiempo, forecasting tabular y walk-forward validation | Metro Interstate Traffic Volume o equivalente |
| 4 | 2026-05-08 | Recommendation systems | MovieLens |
| 5 | 2026-05-09 | Representación, clustering aplicado y confiabilidad | Online Retail |

> La **Sesión 1** integra tanto la presentación general del curso como el contenido técnico inicial.  
> La actividad del **30/05/2026** corresponde a la sustentación institucional del **Proyecto Integrador (PI)** y **no** hace parte de las clases regulares del curso.

---

## Slides y notebooks

| Sesión | Slides | Notebook |
|---|---|---|
| 1 - Syllabus + evaluación moderna, desbalance y ensembles | [PDF](https://github.com/marcoteran/ml/raw/master/lectures/01_ml_modern_evaluation_imbalance_ensembles.pdf) |  |
| 2 - Boosting moderno y optimización de hiperparámetros con validación correcta | [PDF](https://github.com/marcoteran/ml/raw/master/lectures/02_ml_boosting_optuna.pdf) | [Descargar NB02](https://github.com/marcoteran/ml/blob/master/notebooks/ml_boosting_optuna.ipynb)<br>[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/marcoteran/ml/blob/master/notebooks/ml_boosting_optuna.ipynb)<br>[![Abrir en Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/marcoteran/ml/blob/master/notebooks/ml_boosting_optuna.ipynb) |
| 3 | [PDF](ADD_LINK_S03_SLIDES) | [Descargar NB03](ADD_LINK_NB03_RAW)<br>[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](ADD_LINK_NB03_COLAB)<br>[![Abrir en Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](ADD_LINK_NB03_KAGGLE) |
| 4 | [PDF](ADD_LINK_S04_SLIDES) | [Descargar NB04](ADD_LINK_NB04_RAW)<br>[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](ADD_LINK_NB04_COLAB)<br>[![Abrir en Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](ADD_LINK_NB04_KAGGLE) |
| 5 | [PDF](ADD_LINK_S05_SLIDES) | [Descargar NB05](ADD_LINK_NB05_RAW)<br>[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](ADD_LINK_NB05_COLAB)<br>[![Abrir en Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](ADD_LINK_NB05_KAGGLE) |

---

## Evaluación

| Componente | Peso |
|---|---:|
| Taller modular único | 20% |
| Exposición de temas avanzados | 20% |
| Examen final | 25% |
| Proyecto Integrador (PI) | 35% |

### Examen final
- **Formato:** teórico, opción múltiple
- **Preguntas:** 20
- **Plataforma:** Interactiva
- **Duración efectiva:** 1 horas
- **Ventana:** se activa en la última clase y queda habilitado hasta el domingo a medianoche

### Taller evaluativo — Predicción de accidentalidad

El taller ya se encuentra disponible en Interactiva y corresponde a una evaluación grupal del curso.  
Consiste en desarrollar un flujo completo de **Machine Learning para predicción binaria desbalanceada**, usando una base de datos en SQLite para estimar la ocurrencia de accidentes por barrio y hora.

**Fecha de entrega:** viernes 15 de mayo de 2026, 5:00 p.m.  
**Entregables:** informe en PDF + notebook `.ipynb` ejecutable  
**Entrega:** EAFIT Interactiva  
**Descarga:** [Enunciado del taller](https://github.com/marcoteran/ml/raw/master/homeworks/aprendizaje_automatico_taller_20261.pdf)

El taller evalúa especialmente:

- formulación del problema y construcción del target;
- generación de casos negativos;
- análisis exploratorio y calidad de datos;
- unión de tablas e ingeniería de características;
- manejo de clases desbalanceadas;
- validación temporal y control de fuga de información;
- comparación de modelos y ajuste de hiperparámetros;
- selección de métricas adecuadas, thresholding y matriz de confusión;
- propuesta de uso operativo del modelo;
- recomendación final defendible.

---

## Exposiciones

Cada grupo podrá escoger tema por orden de selección. Se permite una modalidad de hasta 4 integrantes por grupo, según la dinámica del curso. La presentación tendrá una duración de entre 5-10 minutos.
### Entregables
- presentación en PDF;
- repositorio público en GitHub;
- ejemplo computacional reproducible en Python.

### Banco de temas
- Reinforcement Learning
- Federated Learning
- Semi-Supervised Learning
- MLOps / Deployment
- Explainable AI (XAI)
- Conformal Prediction
- Uncertainty Quantification
- Active Learning
- Learning to Rank
- Graph Machine Learning
- Tabular Deep Learning
- Anomaly Detection at Scale
- Continual Learning
- AutoML
- Time-Series Transformers
- TinyML / Edge ML

La asignación del tema se elegirá en orden de acuerdo al tiempo de elección.

---

## Datasets del curso

- **Credit Card Fraud Detection:** métricas, desbalance, thresholds, boosting, taller
- **Metro Interstate Traffic Volume** o equivalente: forecasting, features temporales, walk-forward
- **MovieLens:** recommendation systems, top-N, ALS
- **Online Retail:** segmentación, clustering, representación y confiabilidad

---

## Tools

`Python` · `NumPy` · `pandas` · `scikit-learn` · `matplotlib` · `xgboost` · `lightgbm` · `catboost` · `optuna` · `umap-learn` · `shap`

---

## Recursos recomendados

<details>
<summary><strong>Fundamentos, métricas y validación</strong></summary>

- [Scikit-learn · Model selection and evaluation](https://scikit-learn.org/stable/model_selection.html)
- [Scikit-learn · Metrics and scoring](https://scikit-learn.org/stable/modules/model_evaluation.html)
- [Scikit-learn · Tuning the decision threshold](https://scikit-learn.org/stable/modules/classification_threshold.html)
- [Google Developers · Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course)
- [Made With ML · Machine Learning glossary / practical guides](https://madewithml.com/)

</details>

<details>
<summary><strong>Boosting, tuning y práctica moderna</strong></summary>

- [XGBoost documentation](https://xgboost.readthedocs.io/)
- [LightGBM documentation](https://lightgbm.readthedocs.io/)
- [CatBoost documentation](https://catboost.ai/)
- [Optuna documentation](https://optuna.org/)
- [XGBoost paper](https://arxiv.org/abs/1603.02754)
- [LightGBM paper](https://papers.nips.cc/paper_files/paper/2017/hash/6449f44a102fde848669bdd9eb6b76fa-Abstract.html)

</details>

<details>
<summary><strong>Series de tiempo y forecasting</strong></summary>

- [Scikit-learn · Time-related feature engineering example](https://scikit-learn.org/stable/auto_examples/applications/plot_cyclical_feature_engineering.html)
- [Hyndman · Forecasting: Principles and Practice](https://otexts.com/fpp3/)
- [Skforecast documentation](https://skforecast.org/)
- [Article · Respect the order: cross-validation in time series](https://medium.com/@pacosun/respect-the-order-cross-validation-in-time-series-7d12beab79a1)

</details>

<details>
<summary><strong>Recommendation systems</strong></summary>

- [GroupLens · MovieLens datasets](https://grouplens.org/datasets/movielens/)
- [Implicit library documentation](https://benfred.github.io/implicit/)
- [Dive into Deep Learning · MovieLens example](https://d2l.ai/chapter_recommender-systems/movielens.html)
- [Article · A practical guide to building recommender systems](https://towardsdatascience.com/a-guide-to-recommender-systems-6c0f0f1a7e47)

</details>

<details>
<summary><strong>Clustering, calibración y confiabilidad</strong></summary>

- [Scikit-learn · Clustering](https://scikit-learn.org/stable/modules/clustering.html)
- [Scikit-learn · Novelty and outlier detection](https://scikit-learn.org/stable/modules/outlier_detection.html)
- [Scikit-learn · Probability calibration](https://scikit-learn.org/stable/modules/calibration.html)
- [Article · Probability calibration for imbalanced datasets](https://medium.com/data-science/probability-calibration-for-imbalanced-dataset-64af3730eaab)

</details>

<details>
<summary><strong>Videos y charlas</strong></summary>

- [TED · Jeremy Howard — The wonderful and terrifying implications of computers that can learn](https://www.ted.com/talks/jeremy_howard_the_wonderful_and_terrifying_implications_of_computers_that_can_learn)
- [StatQuest · ROC and AUC, Clearly Explained!](https://www.youtube.com/watch?v=4jRBRDbJemM)
- [StatQuest · Precision, Recall, Sensitivity and Specificity](https://www.youtube.com/watch?v=vP06aMoz4v8)
- [StatQuest · XGBoost in Python from Start to Finish](https://www.youtube.com/watch?v=GrJP9FLV3FE)
- [StatQuest · XGBoost Part 1](https://www.youtube.com/watch?v=OtD8wVaFm6E)
- [StatQuest · XGBoost Part 2](https://www.youtube.com/watch?v=8b1JEDvenQU)
- [YouTube · Stanford / recommender systems lecture](https://www.youtube.com/watch?v=GIcuSNAAa4g)

</details>

<details>
<summary><strong>Libros recomendados</strong></summary>

- Bishop · *Pattern Recognition and Machine Learning*
- Murphy · *Machine Learning: A Probabilistic Perspective*
- Hastie, Tibshirani, Friedman · *The Elements of Statistical Learning*
- Géron · *Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow*
- Aggarwal · *Recommender Systems: The Textbook*

</details>

---

## Estructura del repositorio

```text
ml/
├── README.md
├── lectures/
├── notebooks/
├── homeworks/
├── projects/
├── aditionalmaterial/
└── _assets/
````

---

## Nota final

Este repositorio está pensado como una **base central del curso**:
no solo para descargar PDFs, sino para seguir la ruta completa de clase, práctica, evaluación y estudio autónomo.