# Lead Scoring Predictivo para Optimización Comercial

## Descripción general

Este proyecto desarrolla un sistema de scoring automático de leads utilizando técnicas avanzadas de Machine Learning, con el objetivo de optimizar la gestión comercial y priorizar los contactos con mayor probabilidad de conversión.

## Objetivos del proyecto

* Identificar los leads más valiosos para maximizar la tasa de conversión.
* Facilitar la toma de decisiones comerciales con base en datos objetivos.
* Proveer una solución fácil de integrar en sistemas CRM mediante un modelo reutilizable.

## Tecnologías y librerías utilizadas

* **Python 3.12**
* **Pandas, NumPy, Matplotlib**
* **Scikit-learn**
* **XGBoost**
* **Imbalanced-learn**
* **SHAP**
* **Jupyter Notebook**

## Fuente de los datos

El dataset original de leads utilizado en este proyecto ha sido obtenido de Kaggle:

* [Lead Scoring Dataset – Kaggle](https://www.kaggle.com/datasets/amritachatterjee09/lead-scoring-dataset/code)

Agradezco a los autores y la comunidad de Kaggle por poner estos datos a disposición para el aprendizaje y desarrollo de proyectos de ciencia de datos.

1. **Clonar el repositorio:**

   ```
   git clone https://github.com/Guzurti/lead-scoring-bootcamp.git
   cd lead-scoring-bootcamp
   ```
2. **Instalar dependencias (recomendado en entorno virtual):**
   ```
   pip install -r requirements.txt
   ```
*(El archivo `requirements.txt` ya está incluido en este repositorio, con todas las librerías necesarias).*

3. **Ejecutar el notebook** en Jupyter o Visual Studio Code.

4. **Seguir el flujo** de preprocesado, entrenamiento, evaluación y predicción sobre nuevos leads.

## Resultados principales

* Modelos entrenados y validados: **Random Forest** y **XGBoost**.
* **Métricas finales (test externo):**

  * XGBoost ROC-AUC: 0.76
  * Random Forest ROC-AUC: 0.74
* Visualización de curvas ROC, matriz de confusión y análisis SHAP incluidos.

## Integración en CRM

El modelo entrenado se ha guardado con `joblib`, permitiendo su integración fácil en sistemas comerciales. Se puede desplegar como microservicio o integrar en el flujo de datos del CRM, ofreciendo scoring en tiempo real para cada nuevo lead.

## Futuras líneas de mejora

* Probar nuevas técnicas de ingeniería de features.
* Actualización y reentrenamiento periódico con datos recientes.
* Integración directa en el CRM de la empresa.
* Incorporar feedback de los asesores comerciales.

## Autor

Fernando Egusquiza Martín
[https://www.linkedin.com/in/feregus/](https://www.linkedin.com/in/feregus/)
Julio 2025

## Referencias

* [Scikit-learn documentation](https://scikit-learn.org/)
* [XGBoost documentation](https://xgboost.readthedocs.io/)
* [Imbalanced-learn documentation](https://imbalanced-learn.org/)
* [SHAP documentation](https://shap.readthedocs.io/)
