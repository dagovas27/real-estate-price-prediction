# 🏠 Real Estate Price Prediction

Modelo de Machine Learning para predecir precios de vivienda, desarrollado como parte de una competencia en Kaggle. Incluye una aplicación interactiva desplegada en Streamlit para consulta de predicciones.

---

## Resultados del modelo

| Métrica | Valor |
|--------|-------|
| R² | 0.838 |
| RMSE | ~$19,400 USD |

---

## Modelos evaluados

- Árbol de Decisión (Regresión)
- Random Forest
- Boosting / Gradient Boosting
- XGBoost
- Redes Neuronales (RN)
- Support Vector Machine (SVM)

**Optimización de hiperparámetros:** GridSearchCV · RandomizedSearchCV · Algoritmos Genéticos

---

## Estructura del repositorio

real-estate-price-prediction/
│
├── Preparacion_Datos_Proyecto_Final_MD.ipynb   # Limpieza y EDA
├── MD_PF_PipeLine.ipynb                        # Pipeline de preprocesamiento
├── MD_Aprendizaje_Proyecto_Final_MD.ipynb      # Entrenamiento y evaluación de modelos
├── Hiperparametrizacion_de_Modelos_PF_MD.ipynb # Optimización de hiperparámetros
├── Copia_de_myAppInmoT.ipynb                   # App Streamlit
├── output_Sales.html                           # Visualización de resultados
└── README.md
---

## Tecnologías utilizadas

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189A44?style=flat)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=flat&logo=kaggle&logoColor=white)

---

## Cómo ejecutar

```bash
# Clonar el repositorio
git clone https://github.com/dagovas27/real-estate-price-prediction.git
cd real-estate-price-prediction

# Instalar dependencias
pip install -r requirements.txt

# Ejecutar la app
streamlit run Copia_de_myAppInmoT.ipynb
```

---

## Autores

- **Daniel Vásquez** — [@dagovas27](https://github.com/dagovas27)
- **Mariana Gonzalez** — [@dagovas27](https://github.com/dagovas27)
- Desarrollado en colaboración como proyecto académico — Universidad Pontificia Bolivariana
