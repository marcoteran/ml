[![banner](/_assets/pics/bannerAI.jpg)](https://github.com/marcoteran/ml)

# SI7009 · Aprendizaje Automático
## Maestría en Ciencia de Datos y Analítica · Universidad EAFIT · 2026-1

<p align="left">
  <img src="https://img.shields.io/badge/Universidad-EAFIT-0F2747?style=for-the-badge" alt="EAFIT">
  <img src="https://img.shields.io/badge/Maestría-Ciencia%20de%20Datos%20y%20Analítica-173B63?style=for-the-badge" alt="Maestría">
  <img src="https://img.shields.io/badge/Curso-SI7009-1F2937?style=for-the-badge" alt="SI7009">
  <img src="https://img.shields.io/badge/Semestre-2026--1-6B7280?style=for-the-badge" alt="2026-1">
</p>

> Repositorio oficial del curso **Aprendizaje Automático**.  
> Aquí se centralizan las diapositivas, notebooks, materiales de apoyo, lineamientos de evaluación y recursos complementarios del curso.

---

## Visión del curso

**Aprendizaje Automático** es un curso intensivo y aplicado de nivel maestría orientado a desarrollar criterio técnico para formular problemas de modelado, evaluar correctamente, comparar modelos modernos con rigor y comunicar resultados de forma reproducible.

El curso no está diseñado como una lista enciclopédica de algoritmos. Su foco está en decisiones de Machine Learning que realmente importan en práctica:

- elegir métricas correctas;
- validar sin leakage;
- manejar problemas desbalanceados;
- optimizar modelos boosted con criterio;
- tratar datos temporales correctamente;
- construir recomendadores básicos reproducibles;
- segmentar, detectar anomalías y diagnosticar confiabilidad del modelo.

El repositorio está organizado para que cada sesión tenga una lectura clara: **slides**, **notebook guía**, **material complementario** y, donde aplique, **recursos para evaluación o trabajo autónomo**.

---

## Información general

- **Curso:** SI7009 - Aprendizaje Automático
- **Programa:** Maestría en Ciencia de Datos y Analítica
- **Universidad:** Universidad EAFIT
- **Profesor:** [Marco Teran](https://marcoteran.github.io/)
- **Modalidad:** Presencial intensiva
- **Semestre:** 2026-1

---

## Calendario de clases

| Sesión | Fecha | Horario | Tema central | Slides | Notebook | Dataset principal |
|---|---:|---:|---|---|---|---|
| 0 | Por publicar | Por publicar | Presentación del curso y lineamientos | [PDF](ADD_LINK_SYLLABUS_SLIDES) | — | — |
| 1 | 2026-04-24 | 5:00 PM–9:00 PM | Evaluación moderna, desbalance y fundamento de ensembles | [PDF](ADD_LINK_S01_SLIDES) | [Notebook](ADD_LINK_NB01) | Credit Card Fraud Detection |
| 2 | 2026-04-25 | 8:00 AM–12:00 PM | Boosting moderno y optimización de hiperparámetros | [PDF](ADD_LINK_S02_SLIDES) | [Notebook](ADD_LINK_NB02) | Credit Card Fraud Detection |
| 3 | 2026-05-02 | 8:00 AM–12:00 PM | Series de tiempo, forecasting tabular y walk-forward validation | [PDF](ADD_LINK_S03_SLIDES) | [Notebook](ADD_LINK_NB03) | Metro Interstate Traffic Volume o equivalente |
| 4 | 2026-05-08 | 5:00 PM–9:00 PM | Recommendation systems y ampliación del problema de ML | [PDF](ADD_LINK_S04_SLIDES) | [Notebook](ADD_LINK_NB04) | MovieLens |
| 5 | 2026-05-09 | 8:00 AM–11:00 AM | Representación, clustering aplicado y confiabilidad | [PDF](ADD_LINK_S05_SLIDES) | [Notebook](ADD_LINK_NB05) | Online Retail |

> **Nota:** El espacio del **30 de mayo de 2026** corresponde a la dinámica institucional de sustentación del **Proyecto Integrador (PI)** y **no** forma parte de la docencia regular del curso.

---

## Ruta académica del curso

### Sesión 0 · Presentación del curso
Panorama general, evaluación, estructura del curso, relación con PI, exposiciones, taller modular y dinámica de trabajo.

### Sesión 1 · Evaluación moderna, desbalance y fundamento de ensembles
- workflow moderno de Machine Learning;
- árboles como fundamento conceptual;
- bias–variance;
- bagging vs boosting;
- accuracy trap;
- PR-AUC vs ROC-AUC;
- precision, recall, F1, Recall@k;
- threshold tuning;
- class weights, resampling y SMOTE.

### Sesión 2 · Boosting moderno y optimización de hiperparámetros
- XGBoost, LightGBM y CatBoost;
- regularización, subsampling y early stopping;
- comparación robusta entre modelos;
- Bayesian Optimization con Optuna;
- validación cruzada dentro del loop de tuning;
- criterio de selección final del modelo.

### Sesión 3 · Series de tiempo y validación temporal
- forecasting tabular/global;
- lag features y rolling windows;
- codificación temporal cíclica;
- horizonte de predicción;
- walk-forward validation;
- leakage temporal;
- métricas temporales.

### Sesión 4 · Recommendation systems
- utility matrix;
- explicit vs implicit feedback;
- top-N recommendation;
- ALS;
- evaluación de recomendadores;
- cold start;
- interpretación mínima útil para modelos de personalización.

### Sesión 5 · Clustering, segmentación y confiabilidad
- PCA, t-SNE y UMAP;
- K-Means y Mini-Batch K-Means;
- customer segmentation;
- outlier detection con Isolation Forest y LOF;
- calibration curves;
- drift básico y lectura operativa del modelo.

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
- **Número de preguntas:** 20
- **Plataforma:** Interactiva
- **Duración efectiva:** 2 horas
- **Ventana:** se activa en la última clase y queda disponible hasta el domingo a medianoche

### Taller modular único
Se publicará en la **segunda semana** del curso y se entregará en la **última sesión**.  
Su objetivo es recorrer un problema real de predicción binaria desbalanceada de principio a fin:

- formulación del problema;
- definición de baseline;
- métrica principal y secundaria;
- validación;
- boosting;
- thresholding;
- calibración;
- decisión final defendible.

---

## Exposiciones de temas avanzados

Las exposiciones amplían el mapa del curso hacia temas modernos que no se cubren en las sesiones centrales.

### Condiciones generales
- asignación por orden de escogencia;
- se permite trabajo individual o en pareja;
- cada exposición debe incluir:
  - motivación;
  - fundamento técnico;
  - ejemplo computacional en Python;
  - caso de uso real;
  - presentación en PDF;
  - repositorio GitHub público reproducible.

### Banco de temas
- Sistemas de recomendación avanzados
- Aprendizaje por refuerzo
- Aprendizaje semi-supervisado
- Aprendizaje federado
- MLOps / Deployment
- Problemas de clasificación altamente desbalanceados
- Incorporación de restricciones en modelos
- Explainable AI (XAI)
- Graph Neural Networks
- Learning to Rank
- Uplift Modeling
- Active Learning
- Continual Learning
- Time-Series Transformers
- Tabular Deep Learning
- AutoML
- Synthetic Data Generation
- Fairness in Machine Learning
- Anomaly Detection at Scale
- Conformal Prediction
- Uncertainty Quantification
- TinyML / Edge ML

---

## Datasets canónicos del curso

| Dataset | Uso principal |
|---|---|
| **Credit Card Fraud Detection** | Desbalance, métricas, thresholds, rebalancing, boosting, taller modular |
| **Metro Interstate Traffic Volume** o equivalente | Forecasting tabular, lags, ventanas, leakage temporal |
| **MovieLens** | Recommendation systems, top-N, ALS |
| **Online Retail** | Segmentación, clustering, representación y confiabilidad |

La filosofía del curso es trabajar con **pocos datasets bien elegidos** para profundizar decisiones metodológicas, en lugar de usar muchos ejemplos superficiales.

---

## Herramientas y stack técnico

### Lenguaje y entorno
- Python 3.11+
- Jupyter Notebook / JupyterLab
- VS Code o equivalente
- Git y GitHub

### Librerías principales
- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`
- `seaborn` *(solo cuando aporte valor exploratorio)*
- `xgboost`
- `lightgbm`
- `catboost`
- `optuna`
- `scipy`
- `statsmodels` *(si aplica para apoyo temporal)*
- `implicit` *(para recomendadores ALS, si se usa ese pipeline)*
- `umap-learn`
- `shap` *(solo donde sea útil y no distraiga del objetivo central)*

### Competencias operativas que se esperan del repositorio
- notebooks reproducibles;
- pipelines claros;
- evaluación honesta;
- visualizaciones interpretables;
- código comentado y ordenado;
- resultados fáciles de revisar y reutilizar.

---

## Estructura sugerida del repositorio

```text
ml/
├── README.md
├── lectures/
│   ├── 00_aprendizaje_automatico_presentacion_curso.pdf
│   ├── 01_evaluacion_desbalance_ensembles.pdf
│   ├── 02_boosting_hpo.pdf
│   ├── 03_series_tiempo_walkforward.pdf
│   ├── 04_recommenders_als.pdf
│   └── 05_clustering_confiabilidad.pdf
├── notebooks/
│   ├── NB01_imbalance_metrics_thresholds.ipynb
│   ├── NB02_boosting_optuna.ipynb
│   ├── NB03_time_series_walkforward.ipynb
│   ├── NB04_recommenders_als.ipynb
│   └── NB05_segmentation_reliability.ipynb
├── homeworks/
│   ├── taller_modular_2026_1.pdf
│   └── exposiciones_temas_avanzados.pdf
├── projects/
│   └── proyecto_integrador_guidelines.pdf
├── aditionalmaterial/
│   ├── documentation/
│   ├── cheatsheetsandinfographics/
│   ├── papers/
│   └── books/
└── _assets/
    └── pics/
````

---

## Acceso rápido a materiales

### Slides

* [Presentación del curso](ADD_LINK_SYLLABUS_SLIDES)
* [Sesión 1 · Evaluación, desbalance y ensembles](ADD_LINK_S01_SLIDES)
* [Sesión 2 · Boosting y HPO](ADD_LINK_S02_SLIDES)
* [Sesión 3 · Series de tiempo y validación temporal](ADD_LINK_S03_SLIDES)
* [Sesión 4 · Recommendation systems](ADD_LINK_S04_SLIDES)
* [Sesión 5 · Clustering y confiabilidad](ADD_LINK_S05_SLIDES)

### Notebooks

* [NB01 · Imbalance, metrics and thresholds](ADD_LINK_NB01)
* [NB02 · Boosting and Optuna](ADD_LINK_NB02)
* [NB03 · Time series and walk-forward validation](ADD_LINK_NB03)
* [NB04 · Recommenders with ALS](ADD_LINK_NB04)
* [NB05 · Segmentation and reliability](ADD_LINK_NB05)

### Evaluaciones y lineamientos

* [Taller modular único](ADD_LINK_TALLER)
* [Lineamientos de exposiciones](ADD_LINK_PRESENTATIONS)
* [Información de Proyecto Integrador](ADD_LINK_PI_GUIDE)

---

## Instalación del entorno

### Opción recomendada · `conda`

```bash
conda create -n ml_eafit_2026 python=3.11 -y
conda activate ml_eafit_2026
pip install numpy pandas scikit-learn matplotlib seaborn scipy statsmodels \
            xgboost lightgbm catboost optuna umap-learn shap jupyterlab notebook
```

### Dependencias opcionales

```bash
pip install implicit
```

### Ejecutar notebooks

```bash
jupyter lab
```

---

## Material de apoyo

### Documentación y setup

* [Cómo instalar Anaconda](ADD_LINK_ANACONDA_GUIDE)
* [Documentación oficial de Anaconda](https://docs.anaconda.com/anaconda/install/)
* [Documentación oficial de Jupyter](https://docs.jupyter.org/en/latest/)
* [Documentación oficial de scikit-learn](https://scikit-learn.org/stable/)
* [Optuna Documentation](https://optuna.org/)
* [XGBoost Documentation](https://xgboost.readthedocs.io/)
* [LightGBM Documentation](https://lightgbm.readthedocs.io/)
* [CatBoost Documentation](https://catboost.ai/)
* [UMAP Documentation](https://umap-learn.readthedocs.io/)

### Cheatsheets y recursos rápidos

* [Python Cheatsheet](ADD_LINK_PYTHON_CHEATSHEET)
* [Pandas User Guide](https://pandas.pydata.org/docs/user_guide/index.html)
* [Scikit-learn Model Evaluation Guide](https://scikit-learn.org/stable/modules/model_evaluation.html)
* [Scikit-learn Cross-Validation Guide](https://scikit-learn.org/stable/modules/cross_validation.html)

---

## Material complementario recomendado

### Libros

* Christopher M. Bishop · *Pattern Recognition and Machine Learning*
* Kevin P. Murphy · *Machine Learning: A Probabilistic Perspective*
* Trevor Hastie, Robert Tibshirani, Jerome Friedman · *The Elements of Statistical Learning*
* Aurélien Géron · *Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow*
* Charu C. Aggarwal · *Recommender Systems: The Textbook*
* Max Kuhn, Kjell Johnson · *Feature Engineering and Selection*

### Papers / referencias útiles

* Leo Breiman · *Random Forests*
* Friedman · *Greedy Function Approximation: A Gradient Boosting Machine*
* Chen & Guestrin · *XGBoost: A Scalable Tree Boosting System*
* Ke et al. · *LightGBM: A Highly Efficient Gradient Boosting Decision Tree*
* Dorogush et al. · *CatBoost*
* Hyndman & Koehler · *Another Look at Measures of Forecast Accuracy*
* Rendle et al. · referencias clave en recomendación implícita
* papers aplicados sobre calibration, drift y reliability según el avance del curso

### Videos / charlas útiles

* Jeremy Howard · *The Wonderful and Terrifying Implications of Computers That Can Learn*
* conferencias introductorias de gradient boosting, model evaluation y recommendation systems
* charlas de MLOps, XAI o conformal prediction como apoyo para exposiciones

---

## Proyecto Integrador (PI)

Este curso se articula con el **Proyecto Integrador** del semestre, pero no se reduce a él.

Desde la perspectiva de Aprendizaje Automático, el PI debe reflejar:

* formulación correcta del problema analítico;
* definición razonable del target;
* selección de métricas;
* esquema de validación defendible;
* comparación justa entre modelos;
* lectura técnica de resultados;
* interpretación suficiente para comunicación académica y aplicada.

El PI aporta el **35%** de la nota del curso, pero su evaluación pertenece a la lógica transversal del programa.

---

## Filosofía de este repositorio

Este repositorio no es un simple contenedor de PDFs.
Está pensado como un espacio de trabajo académico donde cada material cumple una función precisa:

* las **diapositivas** organizan la narrativa conceptual;
* los **notebooks** muestran la ejecución reproducible;
* el **taller** obliga a tomar decisiones defendibles;
* las **exposiciones** amplían la frontera temática;
* los **materiales complementarios** ayudan a estudiar con más profundidad.

La meta no es acumular archivos, sino construir una experiencia coherente de aprendizaje.

---

## Próximamente

Se agregarán los enlaces finales a:

* slides en PDF;
* notebooks completos;
* guía del taller modular;
* lineamientos de exposiciones;
* recursos adicionales del curso.

---

## Contacto

**Profesor:** [Marco Teran](https://marcoteran.github.io/)

Para anuncios oficiales, cambios logísticos y comunicación del curso, revisar:

* **Interac tiva**
* **Microsoft Teams**
* este repositorio

---

## Licencia y uso académico

Los materiales de este repositorio están destinados al uso académico de los estudiantes del curso.
El código y notebooks pueden reutilizarse con fines educativos citando la fuente correspondiente cuando aplique.

---
