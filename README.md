# 🧪 Diabetes Risk Classifier

Este proyecto utiliza técnicas de Machine Learning con **Scikit-Learn** para predecir el riesgo de diabetes a partir de un conjunto de datos clínicos de pacientes (Pima Indians Diabetes Dataset).

## 🎯 Objetivo

Construir un modelo de clasificación binaria que identifique si una persona tiene riesgo de desarrollar diabetes, en base a variables como glucosa, presión arterial, IMC, edad, entre otras.

## 🛠 Herramientas utilizadas

- Python 3
- Pandas, NumPy
- Scikit-Learn
- Matplotlib, Seaborn

## 📂 Estructura

```
diabetes-risk-classifier/
├── data/
│   └── diabetes.csv
├── diabetes-risk-classifier.ipynb
├── README.md
└── requirements.txt
```

## 📊 Dataset

El dataset utilizado es el [Pima Indians Diabetes Database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database), que contiene información médica de mujeres mayores de 21 años.

## 📈 Proceso de análisis

1. Exploración y limpieza del dataset.
2. Escalado de variables con `StandardScaler`.
3. División en conjunto de entrenamiento y prueba (80/20).
4. Entrenamiento de un modelo `RandomForestClassifier`.
5. Validación cruzada (5-fold) para medir la robustez del modelo.
6. Evaluación con métricas: accuracy, precisión, recall, f1-score y ROC AUC.
7. Visualizaciones: matriz de confusión y curva ROC.

## ✅ Resultados

- **Accuracy media (validación cruzada 5-fold)**: 76.6%
- **Accuracy en test set**: 73%
- **ROC AUC**: 0.70

El modelo muestra un buen desempeño general y puede servir como base para sistemas de apoyo al diagnóstico de diabetes.

## 📊 Visualizaciones

Se incluyen:

- ✅ Matriz de confusión con etiquetas personalizadas.
- ✅ Curva ROC con área bajo la curva (AUC) calculada.

## 👤 Autor

**Mailin Villán**  
Científica de datos en salud con doctorado en Ingeniería Biomédica.  
Contacto: mailin.villan@gmail.com  
[LinkedIn](https://www.linkedin.com/in/mailin-adriana-vill%C3%A1n-vill%C3%A1n-55362a23/) | [GitHub](https://github.com/MailinV)
