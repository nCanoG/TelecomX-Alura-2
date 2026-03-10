# TelecomX-Alura-2
Se realizara el Challenge de analisis de datos TelecomX-2

# Predicción de Churn en Telecom X

Este proyecto forma parte del desafío de **Alura Latam** y tiene como objetivo desarrollar un modelo de Machine Learning capaz de predecir la cancelación de clientes (Churn) para una empresa de telecomunicaciones. El análisis permite identificar los factores críticos que influyen en la salida de usuarios y proponer estrategias de retención basadas en datos.

## Tecnologías Utilizadas
* **Lenguaje:** Python 3.x
* **Entorno:** Google Colab / Jupyter Notebook
* **Bibliotecas Principales:** * `Pandas` y `NumPy` (Manipulación de datos)
    * `Scikit-Learn` (Modelado y métricas)
    * `Seaborn` y `Matplotlib` (Visualización)
    * `Imbalanced-learn` (Tratamiento de datos desbalanceados con SMOTE)

## 🛠️ Estructura del Proyecto
1. **Preprocesamiento:** Limpieza de datos, manejo de valores nulos y codificación de variables categóricas.
2. **Feature Engineering:** Creación de nuevas métricas como `Cuentas_Diarias` y normalización de variables numéricas.
3. **Modelado:** Entrenamiento y comparativa de modelos:
    * Regresión Logística
    * Random Forest
4. **Evaluación:** Análisis de métricas (Precision, Recall, F1-Score) y matriz de confusión.
5. **Interpretación:** Análisis de importancia de variables y coeficientes.

## 📊 Hallazgos Principales
Tras el análisis de importancia de variables, se identificaron los siguientes puntos clave:

* **Retención:** La **antigüedad (tenure)** es el factor protector más fuerte; a mayor permanencia, menor riesgo de fuga.
* **Riesgo:** El servicio de **Fibra Óptica** presenta la correlación más alta con la cancelación de clientes.
* **Económico:** Los **cargos mensuales** y totales definen perfiles críticos que requieren atención personalizada.



## 📈 Conclusiones y Estrategias
El modelo óptimo seleccionado fue la **Regresión Logística** debido a su equilibrio entre interpretabilidad y rendimiento (Recall de ~0.72). 

### Estrategias Recomendadas:
1. **Fidelización Temprana:** Campañas enfocadas en los primeros 6 meses de antigüedad.
2. **Revisión de Producto:** Auditoría técnica y de precios sobre el plan de Fibra Óptica.
3. **Incentivos de Contrato:** Promover la migración de contratos mensuales a contratos anuales o bianuales.
