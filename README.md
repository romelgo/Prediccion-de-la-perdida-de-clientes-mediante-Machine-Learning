

# Análisis de Datos y Modelado Predictivo - Abandono de cliente 
 - Este proyecto aborda un análisis completo del dataset de abandono de clientes (Churn_Modelling.csv), cubriendo desde la exploración inicial hasta la aplicación de algoritmos de Machine Learning con enfoque profesional y educativo.

## Contenido del proyecto:

**1. Carga y preprocesamiento de datos**
   - Limpieza, tratamiento de valores faltantes, análisis de clases desbalanceadas.

**2. EDA (Análisis Exploratorio de Datos)**
   - Se utilizaron gráficos de correlación, distribución de variables y comparativas a predecir si un cliente abandonará el banco (churn=1) o se mantendrá (churn=0), utilizando sus características demográficas y financieras.

**3. Visualización**
   - Gráficas como histogramas, boxplots, y mapas de calor permitieron representar patrones entre atributos como: edad, género, puntaje crediticio, balance, número de productos, país, etc..

**4. Modelado Predictivo**
   - Se entrenaron múltiples algoritmos de clasificación:

     - Logistic Regression

     - K-Nearest Neighbors

     - Decision Tree

     - Random Forest

     - Support Vector Machine (SVM)

**5. Ajustes para clases desbalanceadas**
   - Se incorporaron estrategias como class_weight='balanced' y SMOTE para mejorar la detección de clases minoritarias (vinos de calidad baja).

**6. Evaluación de modelos**
   - Se usaron métricas como:

     - Accuracy

     - Precision, Recall, F1-score

     - ROC-AUC
   - Se compararon resultados antes y después del balanceo.
